<template>
  <div id="app">
    <div class="banner">
      <h1>Disease & Symtoms</h1>
    </div>
    <router-view/>
  </div>
</template>

<script>
 export default {
   name: 'App',
 };
</script>

<style>
 * {
   margin: 0;
   padding: 0;
 }
 body {
   background: #569099;
 }
 .banner {
   width: 100%;
   background: #93c572;
 }
 .banner h1 {
   padding: 25px;
    color: #fff;
    text-decoration: underline;
  }
</style>
