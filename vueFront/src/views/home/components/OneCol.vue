<template>
    <div class="grid-container">
        <div class="one-row">
            <!-- Content for the upper row -->
            <svg 
 xmlns="http://www.w3.org/2000/svg"
 xmlns:xlink="http://www.w3.org/1999/xlink"
 width="143px" height="140px">
<defs>
<linearGradient id="PSgrad_0" x1="76.604%" x2="0%" y1="0%" y2="64.279%">
  <stop offset="0%" stop-color="rgb(0,153,255)" stop-opacity="1" />
  <stop offset="100%" stop-color="rgb(0,250,255)" stop-opacity="1" />
  <stop offset="100%" stop-color="rgb(255,255,255)" stop-opacity="1" />
</linearGradient>

</defs>
<path fill-rule="evenodd"  fill-opacity="0.8" opacity="0.851" fill="url(#PSgrad_0)"
 d="M142.469,71.234 C142.469,72.952 141.049,74.344 139.297,74.344 C137.577,74.344 136.184,72.999 136.134,71.325 L136.083,71.323 C136.097,70.778 136.125,70.236 136.125,69.687 C136.125,34.617 107.072,6.187 71.234,6.187 C35.396,6.187 6.344,34.617 6.344,69.687 C6.344,86.647 13.151,102.041 24.222,113.431 L24.197,113.454 C24.892,114.024 25.344,114.870 25.344,115.828 C25.344,117.545 23.924,118.937 22.172,118.937 C21.151,118.937 20.253,118.456 19.672,117.722 L19.663,117.731 C7.488,105.228 -0.000,88.319 -0.000,69.687 C-0.000,31.200 31.893,-0.000 71.234,-0.000 C110.576,-0.000 142.469,31.200 142.469,69.687 C142.469,70.102 142.451,70.512 142.437,70.924 C142.447,71.027 142.469,71.128 142.469,71.234 Z"/>
</svg>
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
  padding: 20px;
  text-align: center;
}

.two-row {
  background: #2ecc71;
  padding: 20px;
  text-align: center;
}
</style>