<template>
  <div id="app">
    <Admin/>
    <!-- <SideBar/> -->
    <div class="bg-purple text-white sm:bg-green md:bg-blue md:text-yellow lg:bg-red xl:bg-orange ...">
  Test
</div>
  </div>
</template>

<script>
import Admin from "@/pages/admin/index.vue";
// import SideBar from "@/components/admin/sideBar/sideBar.vue";

export default {
  name: "app",
  components: {
    Admin,
    // SideBar
  },
};
</script>
