<template>
<h2>
  Employee Details:
</h2>
<ul>
  <li>Name:{{this.Employee.name}}</li>
  <li>Age:{{this.Employee.age}}</li>
  <li>Designation:{{this.Employee.designation}}</li>

</ul>
</template>

<script>
export default {
  name: "EmployeeStates",
  data:function(){
    return{
      Employee:{
        name:"Tony",
        age:25,
        designation:"Software"
      },

    }
  }
};
</script>

<style scoped>

</style>