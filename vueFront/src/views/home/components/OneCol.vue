<template>
    <div class="grid-container">
        <div class="one-row">
            <!-- Content for the upper row -->
        </div>
        <div class="two-row">
            <!-- Content for the lower row -->
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.grid-container {
  display: grid;
  grid-template-rows: 2fr 1fr; /* Upper row takes 2/3, lower row takes 1/3 */
  height: 100vh; /* Set the overall height as needed */
}

.one-row {
  background: #3498db;
  padding: 20px;
  text-align: center;
}

.two-row {
  background: #2ecc71;
  padding: 20px;
  text-align: center;
}
</style>