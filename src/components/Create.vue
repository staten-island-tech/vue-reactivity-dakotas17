`<template>
    <div>
<h1>{{ create.name }}</h1>
<img :src="create.image" alt="">
<h2>{{ clicked }}</h2>
<button @clicked="increment">click</button>
    </div>
</template>

<script setup>
import {ref} from "vue";
const props = defineProps({
    create: Object, 
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