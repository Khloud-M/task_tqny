<template>
  <SideBar />
  <div class="container_dashbord">
    <NavBar/>
    <StartEnd/>

    </div>
</template>

<script >
import SideBar from "./SideBar.vue";
import NavBar from "./NavBar.vue";
import StartEnd from "./StartEnd.vue";
export default {
  components: {
    SideBar,
    NavBar,
    StartEnd
  },
  data() {
    return {};
  },
};
</script>
<style scoped>
.container_dashbord {
  width: 90%;
  margin: auto;
}
</style>
