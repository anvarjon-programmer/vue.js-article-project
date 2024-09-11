<template>
   <header>
    <div class="d-flex flex-column flex-md-row align-items-center pb-3 mb-4 border-bottom">
      <a href="/" class="d-flex align-items-center link-body-emphasis text-decoration-none">
        <span class="fs-4" @click="toHomeHandler">A</span>
      </a>

      <nav class="d-inline-flex mt-2 mt-md-0 ms-md-auto">
        <a class="me-3 py-2 link-body-emphasis text-decoration-none" href="#">Register</a>
        <a class="me-3 py-2 link-body-emphasis text-decoration-none" href="#">Login</a>
      </nav>
    </div>
  </header>
</template>
<script>
export default {
  methods:{
    toHomeHandler(){
      return this.$router.push('/')
    }
  }
    
}
</script>
<style>
    
</style>