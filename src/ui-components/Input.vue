<template lang="">
    <div>
        <div class="form-floating">
      <input :type="type" class="form-control":placeholder="placeholder" id="floatingInput">
      <label for="floatingInput">{{label}}</label>
    </div>
    </div>
</template>
<script>
export default {
    name:'Input',
    props:{
        label:String,
        type:String,
        placeholder:String
    }
}
</script>
<style lang="">
    
</style>