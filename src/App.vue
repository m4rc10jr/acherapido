<template>
  <div id="app">
    <Header />
    <router-view></router-view>
  </div>
</template>

<script>
import './styles/global.css';
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'

import Header from './components/template/Header';

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

