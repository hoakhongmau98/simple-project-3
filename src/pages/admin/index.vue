<template>
  <div>
    <div class="h-15 w-full">

    </div>
    <el-form class="w-full" label-width="120px">
       <el-form-item label="Ngày tháng">
          <el-date-picker
            type="datetimerange"
            range-separator="To"
            start-placeholder="Start date"
            end-placeholder="End date"
          />
       </el-form-item>
    </el-form>
  </div>
</template>

<script>
export default {
  layout: "admin",
};
</script>