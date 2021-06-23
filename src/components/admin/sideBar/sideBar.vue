<template>
  <div class="w-16 bg-color-red">
    <nuxt-link :to="'/home'" class="">
        <el-menu-item :index="'/home'">
            <i class="el-icon-eleme"/>
            <template #title>
                <span><slot /></span>
            </template>
        </el-menu-item>
    </nuxt-link>
  </div>
</template>

<script>

export default {
  name: "SideBar",
};
</script>
