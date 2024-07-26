<template>
  <div id="app" class="d-flex">
    <SideBar />
    <div class="content flex-grow-1">
      <HeaderComp />
      <DashboardComp />
    </div>
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue';
import SideBar from './components/SideBar.vue';
import DashboardComp from './components/DashboardComp.vue';

export default {
  components: {
    HeaderComp,
    SideBar,
    DashboardComp,
  },
};
</script>

<style>
#app {
  display: flex;
  height: 100vh;
}

.content {
  display: flex;
  flex-direction: column;
  width: 100%;
}
</style>
