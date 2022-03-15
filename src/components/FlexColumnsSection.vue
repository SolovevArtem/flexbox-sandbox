<template>
  <div class="FlexColumnsSection">
    <div class="FlexColumn">
      <div class="container">
        <div class="FlexColumn__title">Колонки с flex-контейнерами</div>
        <div class="FlexColumn__row">
          <div class="FlexColumn__columns">
            <div class="columns__item">
              <div class="item__row">
                <div class="item__img">
                  <img src="../assets/image.png" alt="" />
                </div>
                <div class="item_body">
                  <div class="item__title">The description for the image</div>
                  <div class="item_text">
                    Pariatur iure ab sunt nesciunt, quibusdam odio iste cumque
                    itaque, ipsa vel exercitationem ullam quos aut nostrum
                    cupiditate fuga quaerat quam animi dolores. Sequi itaque,
                    unde perferendis nemo debitis dolor.
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="FlexColumn__columns">
            <div class="columns__item">
              <div class="item__row">
                <div class="item__img">
                  <img src="../assets/image.png" alt="" />
                </div>
                <div class="item_body">
                  <div class="item__title">The description for the image</div>
                  <div class="item_text">
                    Pariatur iure ab sunt nesciunt, quibusdam odio iste cumque
                    itaque, ipsa vel exercitationem ullam quos aut nostrum
                    cupiditate fuga quaerat quam animi dolores. Sequi itaque,
                    unde perferendis nemo debitis dolor.
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="FlexColumn__columns">
            <div class="columns__item">
              <div class="item__row">
                <div class="item__img">
                  <img src="../assets/image.png" alt="" />
                </div>
                <div class="item_body">
                  <div class="item__title">The description for the image</div>
                  <div class="item_text">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Nobis facilis fuga, illo at. Natus eos, eligendi illum rerum
                    omnis porro ex, magni, explicabo veniam incidunt in quam
                    sapiente ut ipsum.
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="FlexColumn__columns">
            <div class="columns__item">
              <div class="item__row">
                <div class="item__img">
                  <img src="../assets/image.png" alt="" />
                </div>
                <div class="item_body">
                  <div class="item__title">The description for the image</div>
                  <div class="item_text">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Nobis facilis fuga, illo at. Natus eos, eligendi illum rerum
                    omnis porro ex, magni, explicabo veniam incidunt in quam
                    sapiente ut ipsum.
                  </div>
                </div>
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
  name: "FlexColumnsSection",
};
</script>

<style scoped>
.FlexColumnsSection {
}
.FlexColumn {
  
  background-color: #f5f5f5;
  padding: 50px 0px;
}
.container {
}
.FlexColumn__title {
  text-shadow: 1px 1px 0 rgba(0, 0, 0, 0.3);
  font-size: 55px;
  color: #445161;
  text-align:center;
  padding-bottom: 50px;
}
.FlexColumn__row {
   display:flex;
   flex-wrap: wrap;
   margin: 0px 0px;
}
.FlexColumn__columns {
  
 flex: 0 1 50%;
 
}
.columns__item {
  margin: 10px 0px;
}
.item__row {
  display:flex;
}
.item__img {
  flex: 0 0 200px;
}
.item_body {
  flex: 1 1 auto;
  padding: 0px 17px 0px 15px;
}
.item__title {
  text-shadow: 1px 1px 0 rgba(0, 0, 0, 0.2);
  font-size: 20px;
  color: #445161;
  
}
.item_text {
  text-shadow: 1px 1px 0 rgba(0, 0, 0, 0.2);
  font-size: 19px;
  color: rgb(129, 122, 122);
  margin-top: 20px;
}
</style>
