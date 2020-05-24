<template>
  <div id="main" >
      <Header title="喵"/>
      <div id = "content">
        <div class="movie_menu">
            <div class="city_name">
              <span>大连</span>
              <i class="iconfont iconfont-lower-triangle"></i>
            </div>
            <div class="hot_switch">
              <div class="hot_item active">正在热映</div>
              <div class="hot_item">即将上映</div>
            </div>
            <div class="search_entry">
              <i class="iconfont icon-sousuo"></i>
            </div>
        </div>
        <keep-alive>
          <router-link />
        </keep-alive>
      </div>
      <TabBar/>
  </div>
</template>

<script>
import Header from "@/components/Header";
import TabBar from "@/components/TabBar";

export default {
  name:'Movie',
  components :{
    Header,
    TabBar
  }
}
</script>

<style>

</style>