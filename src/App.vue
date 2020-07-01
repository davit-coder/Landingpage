<template>
  <div id="app">
    <h3 class="title-artis mb-2">Woro Widowati - Ya Rasulullah</h3>
    <div class="img-artis mb-2">
      <img src="./assets/rosull.jpg" alt />
    </div>

    <Rbt />
    

    <div class="footer-musik mt-5">
      <footer>
        <p>© 2020 PT Media Musik Proaktif</p>
      </footer>
    </div>
  </div>
</template>

<script>
import Rbt from "./components/Rbt.vue";
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "App",
  components: {
    Rbt
  }
};
</script>

<style>
body {
  background: #171257;
    padding-bottom: 120px;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; */
  text-align: center;
  
  
}

.title-artis {
  background:-webkit-linear-gradient(left, rgba(254,180,178,1) 0%, rgba(250,109,149,1) 80%, rgba(250,109,149,1) 100%);
  padding-top: 50px;
  padding-bottom: 50px;
  color: #171257;
}

.img-artis img {
  border-radius: 100%;
  width: 200px;
}

.footer-musik {
  display: block;
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    text-align: center;
    background:-webkit-linear-gradient(left, rgba(254,180,178,1) 0%, rgba(250,109,149,1) 80%, rgba(250,109,149,1) 100%);
    color: #171257;
    z-index: 2;
}


@media screen and (min-width: 992px) {
    .footer-musik {
      display: flow-root;
        
    }
}
</style>
