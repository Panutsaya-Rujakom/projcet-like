<template>
  <div>
    
    
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      counter: 0,
      fsize:100,
    };
  },
  props: {
    lable: String,
  },
  methods: {
    upFunction: function () {
      this.fsize += 10;
      console.log("fsize = " + this.fsize);
    },
    downFunction: function () {
      this.fsize -= 10;
      console.log(this.fsize);
    },
  },
};
</script> 
<style>
</style>