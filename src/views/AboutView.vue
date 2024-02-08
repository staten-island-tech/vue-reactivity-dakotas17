<template>
  <div class="custom">
    <Create v-for="options in create" 
    :key="create.name" 
    :Destination="create"
/>
    <h1>Design Your Own Cake!</h1>
    
  </div>
</template>

<script setup>
import Create from "@/components/create.vue";
const create = [{
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
        {
          name: "Cascade Mountains",
          International: false,
          price: 400,
          img: "https://images.unsplash.com/photo-1511497584788-876760111969?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1332&q=80&quot",
        },
        {
          name: "Egyptian Exploration",
          International: true,
          price: 800,
          img: "https://images.unsplash.com/photo-1473580044384-7ba9967e16a0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80&quot",
        },
      ]
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
