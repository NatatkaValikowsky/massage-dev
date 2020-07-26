<template lang="pug">
section.types
  .title-block
    .title-block__pre-title.italic Почувствуй Блаженство
    .title-block__title Виды массажа
  .types__items
    .container
      .row
        .col4
        .col-4
          .types-item(style="background-image:url(./static/img/types_1.png)")
            .types-item__inner
              .types-item__descr.italic От любой боли
              .types-item__title
                | Лечебный
                br
                | массаж
              .types-item__button Подробнее
        .col-4
          .types-item(style="background-image:url(./static/img/types_2.png)")
            .types-item__inner
              .types-item__descr.italic Снимет усталость
              .types-item__title
                | Расслабляющий
                br
                | массаж
              .types-item__button.types-item__button_blue Подробнее
        .col-4
          .types-item(style="background-image:url(./static/img/types_3.png)")
            .types-item__inner
              .types-item__descr.italic Для точеной фигурки
              .types-item__title
                | АНТИЦЕЛЛЮЛИТНЫЙ
                br
                | массаж
              .types-item__button Подробнее
        .col-4
          .types-item(style="background-image:url(./static/img/types_4.png)")
            .types-item__inner
              .types-item__descr.italic Для самых нежных
              .types-item__title
                | Детский
                br
                | массаж
              .types-item__button.types-item__button_blue Подробнее
        .col-4
          .types-item(style="background-image:url(./static/img/types_5.png)")
            .types-item__inner
              .types-item__descr.italic Профессиональный
              .types-item__title
                | СПОРТИВНЫЙ
                br
                | массаж
              .types-item__button Подробнее
        .col-4
          .types-item(style="background-image:url(./static/img/types_6.png)")
            .types-item__inner
              .types-item__descr.italic Секретный метод
              .types-item__title
                | МАССАЖ ЛИЦА
                br
                | (скульптура)
              .types-item__button.types-item__button_blue Подробнее
</template>

<script>
export default {
  name: 'types',
  data () {
    return {}
  }
}
</script>

<style lang="scss">
  .types-item{
    background-color: lightcoral;
    width: 300px;
    height: 300px;
    position: relative;
    text-align: center;
    margin-bottom: 150px;
    background-size: cover;
  }

  .types-item__inner{
    background-color: #fff;
    position: absolute;
    top: 250px;
    left: 5%;
    width:90%;
    min-height: 150px;
  }

  .types-item__descr{
    color: #F9A392;
    font-size: 24px;
    margin-top: 15px;
  }

  .types-item__title{
    text-transform: uppercase;
    font-size: 20px;
  }

  .types-item__button{
    background-color: #F9A392;
    color: #fff;
    padding: 10px;
    text-transform: uppercase;
    margin-top: 20px;
    cursor: pointer;
  }

  .types-item__button_blue{
    background-color: #8ED4CC;
  }
</style>
