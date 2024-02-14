<template>
    <div class="card">
<h1>{{ Destination.name }}</h1>
<img :src="Destination.img" alt="">

<button>add to cart</button>
    </div>
   
</template>

<script setup>
import {ref} from "vue";
const props = defineProps({
    Destination: Object, 
});
//clicker logic


</script>

<style scoped>
img{
    width: 250px;
    height: 300px
}
</style>