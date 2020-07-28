<template lang="pug">
section.callback-block
  .callback-inner
    .callback-inner__title Оставь заявку на консультацию
    form
      .input-block
        label(for="name") Ваше имя
        input(type="text",name="name")
      .input-block
        label(for="name") Ваш номер телефона
        input(type="text",name="name")
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
    background-color: #FAF7F7;
    padding: 20px;
    max-width: 450px;
    text-align: center;
  }

  .callback-inner__title{
    text-transform: uppercase;
    padding: 15px;
    font-size: 24px;
  }

  .input-block{
    position: relative;
    width: 80%;
    margin: 30px auto;

    label{
      position:absolute;
      top: 0;
      z-index: 1;
    }

    input{
      border: 1px solid #F9A392;
      width: 100%;
      height: 45px;
      z-index:2;
    }
  }
</style>
