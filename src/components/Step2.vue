<template>
  <div class="border">
    <div class="mt-2">
      <p>Country</p>
      <input type="text" name="country" id="country" placeholder="Enter country name">
    </div>
    <div class="mt-2">
      <p>Phone number</p>
      <input type="text" name="number" id="number" placeholder="Enter phone number">
    </div>
    <div class="mt-2">
      <input class="mr-2" type="checkbox" name="Notify" id="notifications">
      <label> Enable notifications</label>
    </div>
  </div>
</template>

<script>
export default {
name: "Step2"
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