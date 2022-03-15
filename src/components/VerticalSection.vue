<template>
  <div class="VerticalSection">
    <div class="Vertical">
      <div class="container">
        <div class="vertical__title">Вертикальное выравнивание</div>
        <div class="vertical__body">
          <div class="vertical__row">
            <div class="vertical__column vertical__column_1">
              <div class="vertical__item">
                <div class="vertical__subtitle">буду рад</div>
                <div class="vertical__label">подписке</div>
                <div class="vertical__text">
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Repellat dicta distinctio dolor, dolorum veniam iste
                    accusamus, vero mollitia cumque debitis explicabo architecto
                    beatae suscipit sit quibusdam quas excepturi repudiandae
                    minus!
                  </p>
                </div>
                <button class="vertical__btn">Подписаться</button>
              </div>
            </div>

            <div class="vertical__column vertical__column_2">
              <div class="vertical__item">
                <div class="vertical__subtitle">Буду рад</div>
                <div class="vertical__label">Лайку</div>
                <div class="vertical__text">
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Nisi facilis, provident voluptas dolor impedit consequuntur
                    ea temporibus, quas, atque odit rerum. Inventore cupiditate
                    obcaecati, nemo assumenda voluptatem ad consequuntur
                    blanditiis.Lorem ipsum dolor sit amet consectetur
                    adipisicing elit. Nisi facilis, provident voluptas dolor
                    impedit consequuntur eaLorem ipsum dolor sit amet
                    consectetur adipisicing elit. Nisi facilis, provident
                    voluptas dolor impedit consequuntur ea Lorem ipsum dolor sit
                    amet consectetur adipisicing elit. Nisi facilis, provident
                    voluptas dolor impedit consequuntur ea
                  </p>
                </div>
                <button class="vertical__btn">Лайк</button>
              </div>
            </div>

            <div class="vertical__column vertical__column_3">
              <div class="vertical__item">
                <div class="vertical__subtitle">Буду рад</div>
                <div class="vertical__label">комментарию</div>
                <div class="vertical__text">
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Maxime at deserunt debitis aliquam. Dolorem assumenda vitae
                    totam at facere consequatur! Blanditiis nisi consectetur
                    quam vitae officia consequuntur accusamus ipsam magni?
                  </p>
                </div>
                <button class="vertical__btn">Коментировать</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "VerticalSection",
};
</script>

<style scoped>
.VerticalSection {
}
.Vertical {
  padding: 50px 0;
}
.container {
}
.vertical__title {
  text-shadow: 1px 1px 0 rgba(0, 0, 0, 0.2);
  font-size: 55px;
  color: #445161;
  text-align: center;
  margin-bottom: 50px;
}
.vertical__body {
  max-width: 990px;
  margin: 0px auto;
}
.vertical__row {
  display: flex;

  margin: 0px -22.5px;
}
.vertical__column {
  padding: 0px 22.5px;
  display: flex;
  flex: 0 1 33.333%;
}
.vertical__column_1 {
}
.vertical__column_2 {
}
.vertical__column_3 {
}
.vertical__item {
  background-color: #445162;
  border-radius: 5px;
  color: #fff;
  border: 1px solid #445162;
  display: flex;
  flex-direction: column;
  padding: 0px 0px 10px 0px;
  text-align: center;
}
.vertical__subtitle {
  font-size: 24px;
  text-transform: uppercase;
  margin: 15px 0px;
}
.vertical__label {
  text-transform: uppercase;
  background-color: white;
  color: #445161;
  padding: 15px 0;
}
.vertical__text {
  padding: 20px;
  font-size: 16px;
  line-height: 24px;
  flex: 1 1 auto;
}
.vertical__btn {
  display: block;
  margin: 0px 20px;
  text-align: center;
  line-height: 40px;
  background-color: #fff;
  border-radius: 5px;
  color: #445161;
  font-size: 18px;
}
</style>
