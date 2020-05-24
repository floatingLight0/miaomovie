<template>
  <div id="main" title="喵影">
      <Header title="喵影"/>
      <TabBar/>
  </div>
</template>

<script>
import Header from "@/components/Header";
import TabBar from "@/components/TabBar";

export default {
  name:'Cinema',
  components :{
    Header,
    TabBar
  }
}
</script>

<style>

</style>