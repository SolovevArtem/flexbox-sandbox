<template>
  <div class="WhatSection">
    <div class="what">
      <div class="container">
        <div class="what__row">
          <div class="what__img">
            <img src="../assets/graph.png" alt="" />
          </div>
          <div class="what__body">
            <div class="what__title">Что такое FlexBox?</div>
            <div class="what__text">
              <p>
                Flexbox - это целый модуль, содержащий в себе набор свойств и их
                значений как для родителя flex-контейнера так и для его дочерних
                элементов flex-элементов.
              </p>
              <p>
                Основным преимуществом гибкой FLEX разметки является возможность
                изменять ширину/высоту пространство вокруг и порядок
                flex-элементов, для того чтобы наилучшим образом заполнить
                доступное пространство flex-контейнера
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "WhatSection",
};
</script>

<style scoped>
.WhatSection {
}
.what {
    padding: 50px 0;
}
.container {
}
.what__row {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  
}
.what__img {
   margin-right: 36px;
}
.what__body {
  color: #3333;
}
.what__title {
  text-shadow: 1px 1px 0 rgba(0, 0, 0, 0.3);
  font-size: 55px;
}
.what__text {
  text-shadow: 1px 1px 0 rgba(0, 0, 0, 0.3);
  font-size: 20px;
}
.what__text > p{
    margin: 36px 0;
}
</style>
