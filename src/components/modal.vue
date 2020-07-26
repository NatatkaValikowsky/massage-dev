<template lang="pug">
  .modal__wrapper
    .modal__body
      .modal__inner Внутренняя часть модалки
</template>

<script>
export default {
  name: 'modal',
  data () {
    return {}
  }
}
</script>

<style lang="scss">
  .modal__wrapper{
    width: 100%;
    height: 100%;
    background-color: rgba(0,0,0,.4);
    /*display: flex;*/
    justify-content: center;
    align-items: center;
    position: fixed;
    top: 0;
    left: 0;
    display: none;
  }

  .modal__body{
    background-color: #fff;
  }
</style>
