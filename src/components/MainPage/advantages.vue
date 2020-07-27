<template lang="pug">
section.advantages
  .title-block
    .title-block__pre-title.italic Почему Именно Я?
    .title-block__title Преимущества
  .container
    .adv-items
      .adv-item
        img.adv-item__img(src="/static/img/adv_1.png",width="70%",height="auto")
        .adv-item__text СОВРЕМЕННЫЕ инструменты и средства
      .adv-item
        img.adv-item__img(src="/static/img/adv_2.png",width="70%",height="auto")
        .adv-item__text ВСЕ АБСОЛЮТНО безопасно и стерильно
      .adv-item
        img.adv-item__img(src="/static/img/adv_3.png",width="70%",height="auto")
        .adv-item__text авторская методика массажа
      .adv-item
        img.adv-item__img(src="/static/img/adv_4.png",width="70%",height="auto")
        .adv-item__text УЮТНАЯ домашняя атмосфера
    a.adv-items__button.button Оставить заявку
</template>

<script>
export default {
  name: 'advantages',
  data () {
    return {}
  }
}
</script>

<style lang="scss">
  .advantages{
    margin-top: 50px;
  }

  .adv-items{
    display:flex;
    flex-wrap: wrap;
  }

  .adv-item{
    text-align: center;
    width: 25%;
    border: 1px solid #F9A392;
    border-bottom: 5px solid #F9A392;
  }

  .adv-item__text{
    text-transform: uppercase;
    font-size: 20px;
    width: 80%;
    margin: 20px auto;
  }

  a.adv-items__button{
    width: 300px;
    text-align: center;
    display: block;
    margin: 30px auto;
  }
</style>
