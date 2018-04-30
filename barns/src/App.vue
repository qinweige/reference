<template>
    <div class="container">
        <app-sidebar :messages="msg"></app-sidebar>
    </div>
</template>

<script>
  import Sidebar from './Sidebar.vue';
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    appSidebar: Sidebar
  }
}
</script>

<style>

</style>
