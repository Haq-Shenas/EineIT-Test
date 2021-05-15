<template>
  <div class="card" style="width: 18rem">
    <img src="../assets/logo.png" class="card-img-top" alt="..." />
    <div class="card-body">
      <h5 class="card-title">{{cardtitle}}</h5>
      <p class="card-text">
        {{cardtext}}
      </p>
      <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
  </div>
</template>

<script>
export default {
    name: "card",
    props: ['cardtitle','cardtext']
    
};
</script>

<style>
</style>