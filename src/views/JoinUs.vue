<template>
  <h1>
    HubSportForm
    <div id="hubspotForm" v-once></div>
  </h1>
</template>

<script>
export default {
  mounted() {
    const script = document.createElement("script");
    script.src = "https://js.hsforms.net/forms/v2.js";
    document.body.appendChild(script);
    script.addEventListener("load", () => {
      if (window.hbspt) {
        window.hbspt.forms.create({
          portalId: "8586820",
          formId: "a20bffb0-afff-4230-852f-917e8c9813f7",
          target: "#hubspotForm",
        });
      }
    });
  },
};
</script>
