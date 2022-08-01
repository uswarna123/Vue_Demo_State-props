<template>
<h2>Hello!</h2>
  <Customer name="Tony" age="25" designation="software"/>
  <EmployeeStates/>
</template>

<script>
import Customer from "@/components/CustomerProps";
import EmployeeStates from "@/components/EmployeeStates";
export default {
  components: {EmployeeStates, Customer}
}
</script>

<style>

</style>
