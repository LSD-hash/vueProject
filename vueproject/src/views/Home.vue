<template>
  <div class="home">

<el-container style="height: 100%; border: 1px solid #eee">
  <el-container>
    
    <el-header style=" font-size: 12px; border-bottom:1px solid #ccc; ">
      <el-row>
        <el-col :span="6">
          <div id="nav">
            <router-link class="homelink" to="/">Home</router-link> |
            <router-link class="homelink" to="/about">About</router-link>
            <router-link class="homelink" to="/about">About</router-link>
            <router-link class="homelink" to="/about">About</router-link>
          </div>
        </el-col>
        <el-col :span="14">      
            <div >
              <el-input 
              placeholder="请输入内容" 
              v-model="searchinput"
              class="input-with-select">

                <el-select 
                  slot="prepend" 
                  v-model="select"
                  placeholder="请选择">

                  <el-option label="餐厅名" value="1"></el-option>
                  <el-option label="订单号" value="2"></el-option>
                  <el-option label="用户电话" value="3"></el-option>
                </el-select>
                <el-button slot="append" icon="el-icon-search"></el-button>
              </el-input>
            </div>
        </el-col>
        <el-col :span="4" style="text-align: right;"> 
            <el-dropdown>
                  <i class="el-icon-setting" style="margin-right: 15px"></i>
                  <el-dropdown-menu slot="dropdown">
                    <el-dropdown-item>查看</el-dropdown-item>
                    <el-dropdown-item>新增</el-dropdown-item>
                    <el-dropdown-item>删除</el-dropdown-item>
                  </el-dropdown-menu>
            </el-dropdown>
            <span>王小虎</span>
        </el-col>
      </el-row>
      


    </el-header>
    
    <el-main>
        <el-row style="margin: 15px">
          <el-col :span="6">
            <div>
              <el-radio-group v-model="homeradio1">
                <el-radio-button label="上海"></el-radio-button>
                <el-radio-button label="北京"></el-radio-button>
                <el-radio-button label="广州"></el-radio-button>
                <el-radio-button label="深圳"></el-radio-button>
              </el-radio-group>
            </div>
          </el-col>
          <el-col :span="18"  style="text-align: right;">
            <el-dropdown>
              <el-button type="primary">
                更多菜单<i class="el-icon-arrow-down el-icon--right"></i>
              </el-button>
              <el-dropdown-menu slot="dropdown">
                <el-dropdown-item>黄金糕</el-dropdown-item>
                <el-dropdown-item>狮子头</el-dropdown-item>
                <el-dropdown-item>螺蛳粉</el-dropdown-item>
                <el-dropdown-item>双皮奶</el-dropdown-item>
                <el-dropdown-item>蚵仔煎</el-dropdown-item>
              </el-dropdown-menu>
            </el-dropdown>
            <el-dropdown>
              <el-button type="primary">
                更多菜单<i class="el-icon-arrow-down el-icon--right"></i>
              </el-button>
              <el-dropdown-menu slot="dropdown">
                <el-dropdown-item>黄金糕</el-dropdown-item>
                <el-dropdown-item>狮子头</el-dropdown-item>
                <el-dropdown-item>螺蛳粉</el-dropdown-item>
                <el-dropdown-item>双皮奶</el-dropdown-item>
                <el-dropdown-item>蚵仔煎</el-dropdown-item>
              </el-dropdown-menu>
            </el-dropdown>
            <el-dropdown>
              <el-button type="primary">
                更多菜单<i class="el-icon-arrow-down el-icon--right"></i>
              </el-button>
              <el-dropdown-menu slot="dropdown">
                <el-dropdown-item>黄金糕</el-dropdown-item>
                <el-dropdown-item>狮子头</el-dropdown-item>
                <el-dropdown-item>螺蛳粉</el-dropdown-item>
                <el-dropdown-item>双皮奶</el-dropdown-item>
                <el-dropdown-item>蚵仔煎</el-dropdown-item>
              </el-dropdown-menu>
            </el-dropdown>


          </el-col>
        </el-row>
      <Waterfall></Waterfall>

      <el-footer >
        <div style="text-align: center;">
          <h1>查看更多内容请登录</h1>
        </div>
      </el-footer>

    </el-main>


  </el-container>


</el-container>



  </div>
</template>

<script>
// @ is an alias to /src
import Waterfall from '@/components/waterfall.vue'

export default {
  name: 'Home',
  components: {
    Waterfall
  },
  data() {
    return{
      searchinput:"",
      select:"",
      homeradio1:"上海",
    }
    }
}
</script>
<style>
  .el-header {
    background-color: #B3C0D1;
    color: #333;
    line-height: 60px;
  }
  
  .el-aside {
    color: #333;
  }
  .homelink{
    margin-left:8px;
    margin-right:8px;
  }

  .el-dropdown {
    vertical-align: top;
  }
  .el-dropdown + .el-dropdown {
    margin-left: 15px;
  }
  .el-icon-arrow-down {
    font-size: 12px;
  }


</style>

