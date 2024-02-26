<template>
  <div class="custom">
    

    <h1>Design Your Own Cake!</h1>

    <h2>Base</h2>
    <button v-bind:class="{vc}">vanilla</button>
    <button v-bind:class="{cc}">chocolate</button>

    <h2>Frosting</h2>
    <button v-bind:class="{vf}">vanilla</button>
    <button v-bind:class="{cf}">chocolate</button>
    <button v-bind:class="{sf}">strawberry</button>

    <h2>Sprinkles</h2>
    <button v-bind:class="{sprinkles}">option 1</button>

    <h2>Candles</h2>
    <button v-bind:class="{candle1}">option 1</button>
    <button v-bind:class="{candle2}">option 2</button>

    <h2>Shape</h2>
    <button v-bind:class="{round}">round</button>
    <button v-bind:class="{square}">square</button>
  </div>

  <h1>Total Ingredients</h1>





</template>

<script setup>


</script>





<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
