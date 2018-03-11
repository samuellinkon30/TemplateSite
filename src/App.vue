<template>
  <div id="app">
<Menu></Menu>
   <router-view/>
       <Footer></Footer>

</div>
</template>

<script>

import Menu from './components/shared-componentes/Menu'
import Footer from './components/shared-componentes/Footer'

export default {
  name: 'App',
  components:
  {
    Footer,
    Menu
  }
}
</script>

<style>

</style>
