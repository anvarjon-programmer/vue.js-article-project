<template>
    <main class="form-signin w-25 m-auto">
  <form class="mt-25">
    <!-- <img class="mb-4" src="/docs/5.3/assets/brand/bootstrap-logo.svg" alt="" width="72" height="57"> -->
    <h1 class="h3 mb-3 fw-normal">Please sign in</h1>
    <Input :label="'Name'" :type="'text'" :placeholder="'Name'"/>
    <Input :label="'Email address'" :type="'text'" :placeholder="'Email address'"/>
    <Input :label="'Password'" :type="'text'" :placeholder="'Password'"/>
    <div class="form-check text-start my-3">
      <input class="form-check-input" type="checkbox" value="remember-me" id="flexCheckDefault">
      <label class="form-check-label" for="flexCheckDefault">
        Remember me
      </label>
    </div>
    <Button type="submit">Register</Button>
    <p class="mt-5 mb-3 text-body-secondary">© 2017–2024</p>
  </form>
</main>
</template>
<script>
export default {
    
}
</script>
<style>
    
</style>