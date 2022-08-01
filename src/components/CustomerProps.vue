<template>
<h2>Customer Details: </h2>
  <ul>
    <li>
      Name:{{name}}
    </li>
    <li>
      Age:{{age}}
    </li>
    <li>
      Designation:{{designation}}
    </li>
  </ul>
</template>

<script>
export default {
  name: `Customer`,
  props:{
    name:{type:String,Required:true},
    age:{type:Number,Required: true},
    designation:{type:String,Required:true}
  }
};
</script>

<style scoped>

</style>