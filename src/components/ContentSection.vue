<template>
  <div class="ContentSection">
    <div class="hi">
      <div class="container">
        <div class="hi__row">
          <div class="hi__body">
            <div class="hi__title">Привет, Друг!</div>
            <ul class="hi_list">
              <li>У тебя все получится!</li>
              <li>Никогда не сдавайся!</li>
              <li>Сегодня ты уже знаешь больше чем вчера!</li>
              <li>Спасибо тебе за поддержку!</li>
            </ul>
          </div>
          <div class="hi__img">
            <img src="../assets/PicImg.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContentSection",
  components: {},
};
</script>

<style>
.ContentSection {
  border: 1px solid black;
}
.hi {
  background-color: #445162;
  min-height: 273px;
  padding: 50px 0;
}

.hi__row {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.hi__body {
  color: white;
}
.hi__title {
  text-shadow: 1px 1px 0 rgba(0, 0, 0, 0.3);
  font-size: 55px;
  margin-bottom: 38px;
} 
.hi_list {
  text-shadow: 1px 1px 0 rgba(0, 0, 0, 0.3);
  font-size: 20px;
}
.hi_list li {
  background: url('../assets/checkicon.png') left no-repeat;
  padding: 0px 0px 0px 36px;
  line-height: 25px;
}

.hi__img {
}
</style>
