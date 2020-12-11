<template>
  <main id="app">
    <img alt="erva emoji" src="./assets/logo.png"> 
    <!-- <HelloWorld msg="brotando..."/> -->
  </main>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
  #app {
    font-family: 'Courier New', Courier, monospace;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 10rem;
  }

  img {
    animation: bounceIn 0.6s;
  }

  @keyframes bounceIn {
  0% {
    opacity: 1;
    transform: scale(.3);
  } 

  50% {
    opacity: 1;
    transform: scale(1.05);
  } 

  70% {
    opacity: 1;
    transform: scale(.9);
  }

  100% {
    opacity: 1;
    transform: scale(1);
  }
}
</style>
