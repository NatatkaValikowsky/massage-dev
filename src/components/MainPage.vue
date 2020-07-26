<template lang="pug">
.main-page
  <!--Главный экран-->
  <offer></offer>
  <!-- Типы массажа -->
  <types></types>
  <!-- Почему именно я? -->
  <advantages></advantages>
  <!-- Новости -->
  <news></news>
  <!-- Блок для формы обратной связи -->
  <callback></callback>
  <!-- Модальное окно -->
  <modal></modal>
</template>

<script>
import offer from './MainPage/offer'
import types from './MainPage/types'
import advantages from './MainPage/advantages'
import news from './MainPage/news'
import callback from './MainPage/callback-block'
import modal from './modal'
export default {
  name: 'MainPage',
  data () {
    return {}
  },
  components: {offer, modal, types, advantages, news, callback}
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');

  @font-face {
    font-family: Inspiration;
    src: url(../assets/inspiration.woff);
  }

  .italic{
    font-family: Inspiration, sans-serif;
  }

  *{
    margin:0;
    padding: 0;
    background-color: transparent;
    font-family: 'Roboto', sans-serif;
  }

  a.button{
    width: 200px;
    background: #F9A392;
    box-shadow: 0 10px 18px rgba(0, 0, 0, 0.25);
    color: #fff;
    padding: 15px 20px;
    font-size: 24px;
    text-transform: uppercase;
    cursor: pointer;
  }

  a.button:hover{
    color:#fff;
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
    margin-bottom: 100px;
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
</style>
