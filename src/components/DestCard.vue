<template>
    <div>
<h1 class="card">{{ Destination.name }}</h1>
<img :src="Destination.img" alt="">
<h2>{{ click }}</h2>
<button @click="increment">add to cart (doesnt work btw not my project)</button>
    </div>
   
</template>

<script setup>
import {ref} from "vue";
const props = defineProps({
    Destination: Object, 
});
//clicker logic
const clicked = ref(0);
function increment(){
    clicked.value++;
}

</script>

<style scoped>
img{
    width: 250px;
    height: 300px
}
</style>