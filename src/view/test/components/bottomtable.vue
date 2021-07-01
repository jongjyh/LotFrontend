<template>
  <div><el-table
          :data="tableData"
          style="width: 100%">
      <el-table-column
              prop="id"
              label="车牌号"
              width="180">
      </el-table-column>
      <el-table-column
              prop="loc"
              label="位置"
              width="180">
      </el-table-column>
      <el-table-column
              prop="lon"
              label="经度">
      </el-table-column>
      <el-table-column
              prop="lat"
              label="纬度">
      </el-table-column>
      <el-table-column
              prop="time"
              label="时间">
      </el-table-column>
  </el-table></div>
</template>

<script>
export default {
  name: 'Bottomtable',
    data() {
        return {
            tableData: [{
                id: '京G10292',
                loc: '北京海淀区',
                lon: '',
                lit: '',
                time: ''
            }]
        }
    }
}
</script>

<style scoped>

</style>
