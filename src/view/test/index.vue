<template>
  <div>
    <el-row :gutter="20">
      <el-col :span="18">
        <mapcopn />
      </el-col>
      <el-col :span="6">
        <Aside />
      </el-col>
    </el-row>
    <el-row>
      <el-col :span="24">
        <bottomtable />
      </el-col>
    </el-row>
  </div>
</template>
<script>

import Bottomtable from './components/bottomtable'
import Aside from './components/aside'
import Mapcopn from './components/mapcopn'
export default {
  name: 'Index',
  components: {
    Mapcopn,
    Aside,
    Bottomtable

  }
}
</script>

<style scoped>

</style>
