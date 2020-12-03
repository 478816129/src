<template>
  <div class="header all-header">
    <!-- logo图标开始 -->
    <div class="header-logo">
      <img src="../../public/img/header/logo2.png" alt="" />
      <span>乐观数据</span>
    </div>
    <!-- logo图标结束 -->
    <!-- 页头列表开始 -->
    <div>
      <el-menu
        :default-active="activeIndex"
        class="el-menu-demo"
        mode="horizontal"
        @select="handleSelect"
      >
        <el-menu-item index="1">首页</el-menu-item>
        <el-submenu index="2">
          <template slot="title">创意直击</template>

          <el-menu-item index="2-1">播主搜索</el-menu-item>
          <el-menu-item index="2-2">领域红人榜</el-menu-item>
          <el-menu-item index="2-3">粉丝飙升榜</el-menu-item>
          <el-menu-item index="2-4">影响传播榜</el-menu-item>
          <el-menu-item index="2-5">新锐小生榜</el-menu-item>
          <el-menu-item index="2-6">区域排行榜</el-menu-item>
          
        </el-submenu>
        <el-submenu index="3">
          <template slot="title">博主发现</template>

          <el-menu-item index="2-1">播主搜索</el-menu-item>
          <el-menu-item index="2-2">领域红人榜</el-menu-item>
          <el-menu-item index="2-3">粉丝飙升榜</el-menu-item>
          <el-menu-item index="2-4">影响传播榜</el-menu-item>
          <el-menu-item index="2-5">新锐小生榜</el-menu-item>
          <el-menu-item index="2-6">区域排行榜</el-menu-item>
          
        </el-submenu>
        <el-submenu index="4">
          <template slot="title">数据洞察</template>

          <el-menu-item index="2-1">播主搜索</el-menu-item>
          <el-menu-item index="2-2">领域红人榜</el-menu-item>
          <el-menu-item index="2-3">粉丝飙升榜</el-menu-item>
          <el-menu-item index="2-4">影响传播榜</el-menu-item>
          <el-menu-item index="2-5">新锐小生榜</el-menu-item>
          <el-menu-item index="2-6">区域排行榜</el-menu-item>
          
        </el-submenu>
        <el-submenu index="5">
          <template slot="title">电商变现</template>

          <el-menu-item index="2-1">播主搜索</el-menu-item>
          <el-menu-item index="2-2">领域红人榜</el-menu-item>
          <el-menu-item index="2-3">粉丝飙升榜</el-menu-item>
          <el-menu-item index="2-4">影响传播榜</el-menu-item>
          <el-menu-item index="2-5">新锐小生榜</el-menu-item>
          <el-menu-item index="2-6">区域排行榜</el-menu-item>
          
        </el-submenu>
        
        
      </el-menu>
      <!-- <div class="header-item">
      <div>
        <a href="#">首页</a>
      </div>
      <div>
        <a href="#">创意直击</a>
        <img src="../../public/img/header/more.png" alt="" />
      </div>
      第一个隐藏页面开始
      <div class="hidden1">
        <ul>
          <li>短视频最新热门TOP</li>
          <li>带货短视频最新TOP</li>
          <li>短视频热门BGM榜单</li>
          <li>热议话题TOP榜单</li>
          <li>最新热搜短视频</li>
          <li>时下热门评论榜单</li>
        </ul>
      </div>
      <div class="">
       <a href="#"></a>
      </div>
    </div>
    页头列表结束 -->
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      activeIndex: "1",
    };
  },
  methods: {
    handleSelect(key) {
      console.log(key);
    },
  },
};
</script>
<style  scoped>
.all-header {
  display: flex;
}
.header-item {
  display: flex;
}
.hidden1 {
  display: none;
}
</style>