<template>
  <div id="app">
    <!-- Part 2 - video and quote -->
    <!-- video -->
    <video 
      width="50%" 
      height="50%"
      autoplay loop preload="auto" 
      playsinline
    >
      <source src="../public/yeezy-ad.mp4" type="video/mp4">
      Your browser does not support the video tag. 
    </video>
    <!-- message -->
    <div>
      <figure class="quote">
        <blockquote>
          '' {{message}} ''
        </blockquote>
        <figcaption>
          &mdash; Kanye West, <cite>Vogue</cite>  </figcaption>
      </figure>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  data: function() {
    return {
      message: "Yeezy 350 V2 coming soon, get ready"
    }
  }
}
</script>

<style>
body {
  background-color:black
}
.quote {
  margin: 5%;
  background: #eee;
  padding: 1em;
  border-radius: 1em;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
