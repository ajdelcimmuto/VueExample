<template>
  <div id="app" class="blue-grey darken-4">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <main class="row">
      <Chat title="Channel 1" class="col"></Chat>
      <Chat title="Channel 2" class="col"></Chat>
      <Chat title="Channel 3" class="col"></Chat>

    </main>
  </div>
</template>

<script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
<script src="http://code.jquery.com/jquery-1.11.0.min.js"></script>


<script>
import Chat from './components/Chat.vue'
export default {
  name: 'app',
  components: {
    Chat
  }
}
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
  }
  @import "https://cdnjs.cloudflare.com/ajax/libs/emojione/2.2.7/assets/css/emojione.min.css";
  @import "https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css";
  @import "https://fonts.googleapis.com/icon?family=Material+Icons";
  @import "https://cdn.jsdelivr.net/emojione/2.2.6/assets/css/emojione.min.css";
  @import "https://fonts.googleapis.com/css?family=Monoton";
</style>
