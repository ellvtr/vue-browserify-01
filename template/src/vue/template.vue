<script>
module.exports = {
  name: "my-comp",
  
  data(){
    return {
      foo: "foo"
    };
  }, // data

  methods: {
  }, // methods

  mounted(){
  } // mounted

}; // module

</script>

<template><span>
  <h1></h1>
  <p>myComp</p>
</span></template>

<style scoped>
span {
  color: red;
}
</style>
