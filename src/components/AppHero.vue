<script>
export default {
  data() {
    return {
      title: "Benvenuti nella mia app con Vite e Vue!"
    };
  }
};
</script>

<template>

  <div class="jumbotron">

    <div class="jumbotron-content">

      <img src="../assets/jumbo.jpg" alt="Jumbotron Image">

      <div class="text-container">

        <h1>{{ title }}</h1>

      </div>

    </div>

  </div>

</template>


<style scoped>

h1 {color: #ffffff;}

img {width: 50%; height: 50%;}

.jumbotron {background-color: #f8f9fa;padding: 2.1rem;margin-bottom: 2rem;border-radius: 0.3rem;box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);}

.jumbotron-content {position: relative;}

.text-container {position: absolute;top: 50%;left: 50%;transform: translate(-50%, -50%);text-align: center;}

</style>

