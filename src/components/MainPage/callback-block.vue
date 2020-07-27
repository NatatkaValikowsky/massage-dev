<template lang="pug">
section.callback-block
  .callback-inner
    .callback-inner__title Оставь заявку на консультацию
</template>

<script>
export default {
  name: 'callback-block',
  data () {
    return {}
  }
}
</script>

<style lang="scss">
  .callback-block{
    margin-top: 0;
    background-image: url(/static/img/callback_bg.png);
    background-size: cover;
    min-height: 350px;
    display:flex;
    justify-content: right;
  }

  .callback-inner{
    margin-right: 150px;
    background-color: #fff;
    padding: 20px;
  }

  .callback-inner__title{
    text-transform: uppercase;
    font-size: 24px;
  }
</style>
