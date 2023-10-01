<template>
  <div class="header_startEnd">
    <span>لوحة التحكم</span>
    <h2>إضافه الحضور و الانصراف</h2>
  </div>
  <div class="startEnd">
    <h3>: تفاصيل العمل</h3>
    <textarea placeholder="التفاصيل"> </textarea>
    <input type="submit" value="نهاية العمل" />
  </div>
</template>
<style  scoped>
.header_startEnd{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin: 25px 0 ;
  padding: 0 10px;
  color: #4e4a41;
  align-items: center;
}
span{
font-size: 18px;
}
.startEnd {
  margin: 15px auto;
  display: flex;
  flex-direction: column;
  padding: 12px;
  border-radius: 5px;
  background-color: white;
  box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.3);
  color: #4e4a41;
  align-items: end;
}
h3 {
  padding: 0 45px;
  font-size: 25px;
  margin-top: 15px;
}
textarea {
  margin: 8px auto;
  border: 1px solid #4e4a41 !important;
  border-style: solid !important;
  width: 95%;
  height: 70px;
  padding: 10px;
  border-radius: 10px;
  direction: rtl;
}
input {
  background-color: #4e4a41;
  color: white;
  padding: 7px 15px;
  border-radius: 10px;
  margin: 20px 42px;
  font-size: 19px;
  transition: all 0.3s linear;
}
input:hover {
  background-color: rgba(78, 74, 65, 0.4);
  color: #4e4a41;
}

</style>
