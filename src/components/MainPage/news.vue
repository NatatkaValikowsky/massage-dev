<template lang="pug">
section.news
  .title-block
    .title-block__pre-title.italic Что Новенького?
    .title-block__title Последние новости и события
  .container
    .row.news-items
      .col-3
        .news-item
          img.news-item__img(src="/static/img/new_1.png",width="95%",height="auto")
          .news-item__date 18.04.2020 / новости
          a(href="#")
            .news-item__title 5 причин, почему вам стоит прийти на сеанс
      .col-3
        .news-item
          img.news-item__img(src="/static/img/new_2.png",width="95%",height="auto")
          .news-item__date 19.04.2020 / новости
          a(href="#")
            .news-item__title шоколадная маска: удовольствие и красота
      .col-3
        .news-item
          img.news-item__img(src="/static/img/new_3.png",width="95%",height="auto")
          .news-item__date 20.04.2020 / новости
          a(href="#")
            .news-item__title чем полезен массаж лица?
      .col-3
        .news-item
          img.news-item__img(src="/static/img/new_4.png",width="95%",height="auto")
          .news-item__date 21.04.2020 / новости
          a(href="#")
            .news-item__title природные средства для массажа
    a.news__button.button Читать блог
</template>

<script>
export default {
  name: 'news',
  data () {
    return {}
  }
}
</script>

<style lang="scss">
  .news{
    margin-top: 50px;
    background-color: #FAF7F7;
    padding-bottom: 70px;

    .title-block{
      padding-top: 50px;
    }
  }

  .news-item{
    width: 97%;
    background-color: #fff;
    border: 1px solid #F9A392;
    border-bottom: 5px solid #F9A392;
    text-align: center;
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
  }

  .news-item__img{
    margin-top: 15px;
  }

  .news-item__date{
    text-transform: uppercase;
    color: #F9A392;
    text-align: left;
    width: 90%;
    margin:5px auto;
    font-weight: 500;
  }

  .news-item__title{
    text-transform: uppercase;
    font-size: 20px;
    margin: 20px auto;
    width: 90%;
    text-align: left;
    min-height: 90px;
  }

  a{
    color: #000;
  }

  a:hover{
    color: #000;
  }

  a.news__button{
    display: block;
    width: 300px;
    text-align: center;
    margin: 30px auto 0 auto;
  }
</style>
