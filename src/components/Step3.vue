<template>
  <div class="border">
    <div class="mt-2">
      <p for="firstName">First name</p>
      <input type="text" id="firstName" placeholder="Enter first name">
    </div>
    <div class="mt-2">
      <p for="secondName">Second name</p>
      <input type="text" id="secondName" placeholder="Enter second name">
    </div>
    <div class="mt-2">
      <input class="mr-2" type="radio">
      <label> I'm not a robot</label>
    </div>
  </div>
</template>

<script>
export default {
name: "Step3"
}
</script>

<style>
.border{
  margin: auto;
  padding: 15px;
  border-radius: 5px;
  width:25vw;  
}
</style>