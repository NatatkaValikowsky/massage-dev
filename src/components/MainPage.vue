<template lang="pug">
.offer
  .container
    .offer__menu
      ul
        li
          a(href="#") Виды массажа
          a(href="#") Блог
          a(href="#") Прайс-лист
          a(href="#") Отзывы
    .offer__inner
      .offer__title Сеанс массажа в Майкопе
      .offer__description от специалиста  с 10-летним стажем
      .offer__inner
        .offer__text.italic Удовольствие гарантировано
        .offer__actions
          .offer__button.button Записаться
          .offer__video
            .offer__video-button
              i.fa.fa-play
            .offer__video-desc Краткое видео о работе сервиса
  <div class="offer__svg">
      <svg xmlns="http://www.w3.org/2000/svg" width="100%" height="auto" viewBox="0 0 24305 2741.844">
          <path id="Фигура_4" fill="#ffffff" class="cls-1" d="M24255,1072l25,1645L0,2767V1122s5045.65,2442.07,10816,847C16586.4,373.929,19233.8-274.214,21632,349S24255,1072,24255,1072Z"/>
      </svg>
  </div>
</template>

<script>
export default {
  name: 'MainPage',
  data () {
    return {
      msg: 'Вот оно мое приложение'
    }
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');

  /*@font-face {
    font-family: Inspiration;
    src*: url(../src/inspiration.woff);
  }*/

  *{
    margin:0;
    padding: 0;
    background-color: transparent;
    font-family: 'Roboto', sans-serif;
  }

  .italic{
    font-family: Inspiration, sans-serif;
  }

  .button{
    width: 200px;
    background: #F9A392;
    box-shadow: 0 10px 18px rgba(0, 0, 0, 0.25);
    color: #fff;
    padding: 15px 20px;
    font-size: 24px;
    text-transform: uppercase;
    cursor: pointer;
  }

  .title-block{
    text-align: center;
  }

  .title-block__pre-title{
    font-size: 36px;
    color: #F9A392;
  }

  .title-block__title{
    font-size: 42px;
    text-transform: uppercase;
    font-weight: 300;
    margin-top: 5px;
    position: relative;
  }

  .title-block__title:after{
    display: block;
    content: "";
    width: 800px;
    height: 44px;
    background-image: url(../assets/title_del.png);
    background-size: contain;
    background-repeat: no-repeat;
    position: absolute;
    bottom: -50px;
    left: 50%;
    margin-left: -400px;
  }

  .offer{
    min-height: 100vh;
    background-image: url(../assets/bg.jpg);
    background-size: cover;
    background-position: right center;
    position: relative;
  }

  .offer .offer__svg{
    position: absolute;
    left:0;
    bottom: -10px;
    width: 100%;
  }

  .offer:before{
    display: block;
    content: "";
    width: 250px;
    height: 250px;
    position:absolute;
    left: 0;
    top: 0;
    background-image: url(../assets/flower_1.png);
    background-size: cover;
  }

  .offer:after {
    display: block;
    content: "";
    width: 270px;
    height: 380px;
    position:absolute;
    right: 0;
    bottom: -50px;
    background-image: url(../assets/flower_2.png);
    background-size: cover;
  }

  .offer__menu ul{
    list-style: none;
    display: flex;
    justify-content: center;
  }

  .offer__menu{
    padding-top: 25px;
  }

  .offer__menu li{
    margin: 0 20px;
  }

  .offer__menu li a{
    text-decoration: none;
    color: #000000;
    font-weight: 500;
  }

  .offer__inner{
    width:50%;
    text-align: center;
  }

  .offer__title{
    font-size: 60px;
    text-transform: uppercase;
    font-weight: bold;
    color: #FC7F66;
    margin-top: 70px;
    line-height: 70px;
  }

  .offer__description{
    font-size: 24px;
    text-transform: uppercase;
    margin-top: 15px;
  }

  .offer__text{
    font-size: 36px;
    margin-top: 50px;
  }

  .offer__actions{
    display: flex;
    margin-top: 100px;
  }

  .offer__video{
    display: flex;
    align-items: center;
    margin-left: 40px;
  }

  .offer__video-button{
    width: 50px;
    height: 50px;
    color: #8ED4CC;
    text-align: center;
    background-color: #fff;
    border-radius: 50%;
    box-shadow: 0 10px 18px rgba(0, 0, 0, 0.25);
    font-size: 24px;
    line-height: 50px;
    padding-left: 3px;
    cursor: pointer;
  }

  .offer__video-desc{
    margin-left: 20px;
    width: 150px;
    text-align: left;
    font-size: 16px;
  }

  .types{
    margin-top: 30px;
  }
</style>
