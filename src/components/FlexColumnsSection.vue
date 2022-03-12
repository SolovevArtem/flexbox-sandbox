<template>
  <div class="FlexColumnsSection">
    <div class="FlexColumn">
      <div class="container">
        <div class="FlexColumn__row">
          <div class="FlexColumn__title">Колонки с flex-контейнерами</div>
          <div class="FlexColumn__body">
            <div class="FlexColumn_container"></div>
            <div class="FlexColumn_container"></div>
            <div class="FlexColumn_container"></div>
            <div class="FlexColumn_container"></div>
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
}
.container {
}
.FlexColumn__row {
}
.FlexColumn__title {
  text-shadow: 1px 1px 0 rgba(0, 0, 0, 0.3);
  font-size: 55px;

  color: #445161;
}
.FlexColumn__body {
  color: #3333;
}
</style>
