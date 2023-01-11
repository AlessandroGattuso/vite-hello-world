<script>
export default{
  name: 'AppTitle',
  data(){
    return{
      title: 'Vue'
    }
  }
}
</script>
<template>
  <nav class="navbar navbar-light bg-dark d-flex justify-content-center">
    <div class="container-fluid">
      <a class="navbar-brand text-light" href="#">
        <img src="/src/assets/vue.svg" alt="" width="30" height="24" class="d-inline-block align-text-top">
        {{title}}
        <i class="fa-solid fa-cart-shopping"></i>
      </a>
    </div>
  </nav>
</template>
<style>
  
</style>