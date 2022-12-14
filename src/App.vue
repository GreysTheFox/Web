<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <UserCard photo_path="../../src/assets/img/70.jpg" nick-name="romashka" Nsn="Иванов Иван" Tn="Иванович" address="Москва" email="example.every@gmail.com" phone-number="+79077776655"/>
</template>

<script>
import UserCard from './components/UserCard.vue'

export default {
  name: 'App',
  components: {
    UserCard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
