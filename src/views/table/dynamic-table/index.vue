<script setup lang="ts" name="DynamicTable">
import FixedHeaderTable from "./fixedHeaderTable.vue";
import UnFixedHeaderTable from "./unFixedHeaderTable.vue";
</script>

<template>
  <div class="dynamic-table-container">
    <p>固定表头</p>
    <FixedHeaderTable />
    <p>不固定表头</p>
    <UnFixedHeaderTable />
  </div>
</template>

<style lang="scss" scoped>
.dynamic-table-container {
  padding: 10px 12px;
  background-color: #ffffff;
}
</style>
