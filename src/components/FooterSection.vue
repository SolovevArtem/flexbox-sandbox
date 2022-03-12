<template>
  <footer class="FooterSection">
    <div class="container">
      <div class="footer__row">
        <div class="footer__text">Artem Solovev 2022</div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterSection",
  components: {},
};
</script>

<style scoped>
.FooterSection {
  display:flex;
  position: absolute;
  bottom: 0;
  width: 100%;

  border: 1px solid green;
}
.container {
}
.footer__row {
}
.footer__text {
}
</style>
