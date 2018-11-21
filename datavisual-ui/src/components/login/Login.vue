<template>

  <el-container>
    <el-main>
      <el-card>
        <el-form label-width="80px">
          <el-form-item label="用户名">
            <el-input type="text"></el-input>
          </el-form-item>

          <el-form-item label="密码">
            <el-input type="password"></el-input>
          </el-form-item>

          <el-form-item>
            <el-button type="primary">登录</el-button>
            <el-button type="reset">重置</el-button>
          </el-form-item>
        </el-form>
      </el-card>
    </el-main>

    <el-footer>
      copyright
    </el-footer>
  </el-container>
</template>

<style>

  .el-container {
    position: fixed;
    width: 100%;
    height: 100%;
    background-color: aliceblue;
  }

  .el-main {
    margin-left: 30%;
    margin-top: 10%;
    width: 450px;
    height: 300px;
  }
</style>

<script>
  export default{
    data () {
      return {msg: '登录页'}
    }
  }
</script>
