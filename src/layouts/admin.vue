<template>
  <div id="app">
    <SideBar />
  </div>
</template>

<script>
import SideBar from "@/components/admin/sideBar/sideBar"
export default {
        name: 'AdminLayout',
        components: {
          SideBar
        },
    };
</script>
