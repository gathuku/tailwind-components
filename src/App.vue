<template>
  <div id="app">
    <div class="text-center">
     <blog-layout></blog-layout>
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import BlogLayout from './components/BlogLayout.vue'
export default {
  name: 'App',
  components: {
    BlogLayout,
  }
}
</script>

<style src="./assets/tailwind.css">
