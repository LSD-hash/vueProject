<template>
  <div class="wrapper">
    <div class="" v-for="item,index in pics" :key="index">
      <div class="wf-item">
        <img class="wf-img" :src="item" alt="" srcset="">
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data(){
    return {
      pics:[
        "https://z3.ax1x.com/2021/09/11/hzMhJ1.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3Dk4.jpg",
        "https://z3.ax1x.com/2021/09/11/hz84K0.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3w0U.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hzMhJ1.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3Dk4.jpg",
        "https://z3.ax1x.com/2021/09/11/hz84K0.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3w0U.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hzMhJ1.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3w0U.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hzMhJ1.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3Dk4.jpg",
        "https://z3.ax1x.com/2021/09/11/hz84K0.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3w0U.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hzMhJ1.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3w0U.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hzMhJ1.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3Dk4.jpg",
        "https://z3.ax1x.com/2021/09/11/hz84K0.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3w0U.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hzMhJ1.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3w0U.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hzMhJ1.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3Dk4.jpg",
        "https://z3.ax1x.com/2021/09/11/hz84K0.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3w0U.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hzMhJ1.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3w0U.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hzMhJ1.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3Dk4.jpg",
        "https://z3.ax1x.com/2021/09/11/hz84K0.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3w0U.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hzMhJ1.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3w0U.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hzMhJ1.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3Dk4.jpg",
        "https://z3.ax1x.com/2021/09/11/hz84K0.jpg",
        "https://z3.ax1x.com/2021/09/11/hz3w0U.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hz8R8s.jpg",
        "https://z3.ax1x.com/2021/09/11/hzMhJ1.jpg",
      ]
    }
  },
  setup() {
    
  },
}
</script>
<style>
.wrapper{
    position: relative;
    width: 1200px;
    margin: 0px auto;
    columns: 6;
    columns-gap: 40px;
    border: 1px solid #66ccff;
} 
.wf-item{
  margin: 10px auto;
}

.wf-item .wf-img{
    width: 100%;
    height: 100%;
}

</style>