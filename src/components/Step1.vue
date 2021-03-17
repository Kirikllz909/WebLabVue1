<template>
  <div class="border">
    <div class="mt-2">
      <p>Favorite animal</p>
      <input type="text" name="animal" id="animal" placeholder="Enter favorite animal">
    </div>
    <div class="mt-2">
      <p>Favorite game</p>
      <input type="text" name="game" id="game" placeholder="Enter favorite game">
    </div>
    <div class="mt-2">
      <p>Favorite book</p>
      <input type="text" name="book" id="book" placeholder="Enter favorite book">
    </div>
  </div>
</template>

<script>
export default {
name: "Step1"
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