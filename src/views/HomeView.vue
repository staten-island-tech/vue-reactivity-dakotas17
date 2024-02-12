<template>
  <div>
<DestCard v-for="destination in destinations" 
:key="destination.name" :Destination="destination"

/>

  </div>
</template>


<script setup>
import DestCard from "@/components/DestCard.vue";
const destinations = [{
          name: "Chocolate Round",
          International: true,
          price: 1300,
          img: "https://tutti-dolci.com/wp-content/uploads/2018/08/Classic-Chocolate-Layer-Cake-1-copy.jpg",
        },
        {
          name: "Chocolate Square",
          International: true,
          price: 800,
          img: "https://ne-mos-bakery.myshopify.com/cdn/shop/products/HFG_ChocCake_Sq_1024x1024@2x.jpg?v=1596492671",
        },
        {
          name: "Vanilla Round",
          International: true,
          price: 1200,
          img: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQELfv4I6rNrFtU5vLiCcvAdLh-dD69SNal9Q&usqp=CAU",
        },
        {
          name: "Vanilla Square",
          International: false,
          price: 900,
          img: "https://sallysbakingaddiction.com/wp-content/uploads/2019/06/vanilla-sheet-cake.jpg",
        },
      ]
</script>

<style scoped>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>