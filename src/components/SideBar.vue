<template>
  <!-- <v-card class="mx-auto" width="300"> -->
  <v-navigation-drawer permanent location="right" style="width: 270px">
    <div class="heading">
      <h2>لوحة تحكم</h2>
      <img src="../assets/logo.png" alt="logo" width="50" />
    </div>
    <hr style="border: 1px solid rgba(78, 74, 65,0.2)">
    <div class="heading">
      <span>خلود</span>
      <img
        src="../assets/image.jpg"
        alt="imageProfile"
        width="40"
        style="border-radius: 50%; border: 2px solid #4e4a41"
      />
    </div>
    <div class="container_list">
      <div class="item_list" v-for="item in groups">
        <h3>{{ item.title }}</h3>
        <v-icon> {{ item.action }}</v-icon>
      </div>
    </div>
  </v-navigation-drawer>
  <!-- </v-card> -->
</template>

<script>
export default {
  data: () => ({
    groups: [
      {
        action: "mdi-calendar-check",
        title: "تسكاتي",
      },
      {
        action: "mdi-calendar-check",
        title: " مهامي",
      },
      {
        action: "mdi-memory",
        title: " مذكراتي",
      },
      {
        action: "mdi-timer-play-outline",
        title: "بدء العمل",
      },
      {
        action: "mdi-bell-check-outline",
        title: " تسجيل حضوري",
      },
    ],
  }),
};
</script>
<style scoped >
.heading {
  margin: 20px 0;
}
img {
  border-radius: 5px;
}
.heading,
.item_list {
  display: flex;
  flex-direction: row;
  padding: 8px 15px;
  align-items: center;
  cursor: pointer;
  width: 100%;
  justify-content: end;
  column-gap: 15px;
  color: #4e4a41;
  transition: all 0.3s linear;
}
.item_list:hover{
  background-color: rgba(78, 74, 65, 0.3);
}
.container_list {
  display: flex;
  flex-direction: column;
  align-items: end;
  row-gap: 25px;
}
li,
a {
  font-size: 20px;
  color: black;
}
span {
  font-size: 20px;
}
/* .v-list-item.v-list-item--link.v-list-item--density-default.v-list-item--one-line.v-list-item--variant-text.v-list-group__header {
  justify-content: space-between !important;
}
.main_title {
  display: flex;
  /* background-color: red; */
  /* justify-content: space-between;
  align-items: center;
}
.v-list-item__append > .v-icon {
  display: none !important;
}
.v-list-item__content {
  text-align: end;
} */
span {
  /* margin: 0 10px; */
  font-size: 19px;
}
</style>
