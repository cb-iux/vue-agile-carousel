<template lang="html">
  <div id="app">
    <agile :arrows="false" :dots="false" :speed="800" :autoplaySpeed="6000"
    :timing="'linear'" :fade="true"
    :autoplay="true" :pauseOnHover="false" class="busemannen">
      <div class="slide slide--1"></div>
      <div class="slide slide--2"></div>
      <div class="slide slide--3"></div>
      <div class="slide slide--4"></div>
      <div class="slide slide--5"></div>
    </agile>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="sass">
  html, body
    width: 100%
    margin: 0

  html, body, #app, .agile, .agile__list, .agile__track
    height: 100%

  .busemannen
    .slide
      background:
        position: center
        size: cover

      height: 100%
      width: 100%

      &--1
        background-image: url(../assets/img/busemannen/busemannen-illustrasjon-retouch.jpg)
      &--2
        background-image: url(../assets/img/busemannen/busemannen-skeleton.jpg)
      &--3
        background-image: url(../assets/img/busemannen/busemannen-ylvis_01.jpg)
      &--4
        background-image: url(../assets/img/busemannen/busemannen-ylvis_02.jpg)
      &--5
        background-image: url(../assets/img/busemannen/busemannen-ylvis_03.jpg)

</style>
