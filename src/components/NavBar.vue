<template>
  <setion class="main_nav">
    <div
      class="image"
      style="
        /* background-color: red; */
        display: flex;
        flex-direction: row;
        align-items: center;
        column-gap: 25px;
      "
    >
      <v-icon>mdi-logout </v-icon>
      <!-- <div class="image">
        <img src="../assets/image.jpg" alt="image_profile" width="30"/>
      </div> -->
      <img
        src="../assets/image.jpg"
        alt="image_profile"
        width="40"
        style="   border-radius: 50%; "
      />
    </div>
    <v-spacer> </v-spacer>
    <p>لوحة التحكم</p>
  </setion>
</template>

<script>
export default {};
</script>

<style>
.main_nav {
  margin: 15px auto;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center !important;
  padding: 12px;
  border-radius: 15px;
  background-color: white;
  box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.3);
  color: #4e4a41;

}
p{
font-size: 18px;
color: #4e4a41;

}
p:nth-of-type(2) {
  color: var(--main-color);
  font-weight: 500;
  display: inline-block;
  margin: 0 5px;
  color: #4e4a41;

}
</style>
