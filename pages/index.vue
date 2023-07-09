<template>
  <main class="container">
      <AppHeader></AppHeader>
     <AppRestaurantInfo></AppRestaurantInfo>
  </main>
</template>

<script>
import AppRestaurantInfo from "@/components/AppRestaurantInfo.vue";
import AppHeader from "@/components/AppHeader.vue";

export default {
    name: "IndexPage",
    components: { AppHeader ,AppRestaurantInfo }
}
</script>
