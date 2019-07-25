<template>
  <div class="home">
    <el-container>
      <el-header>
        <Menu/>
      </el-header>
      <el-main>Main</el-main>
    </el-container>
  </div>
</template>

<script>
// @ is an alias to /src

import Menu from '../components/Menu'
export default {
  name: 'home',
  components: { Menu }
}
</script>
