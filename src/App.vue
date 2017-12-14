<template>

  <div id="app">
        <header>
        <div class="container">
            <nav class="navbar navbar-expand-md navbar-light bg-light px-0">
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <a class="navbar-brand" href="#">
                    <h1>
                        <span class="cor-principal">UMa</span>
                        Cantina
                    </h1>
                </a>
                <div class="collapse navbar-collapse" id="navbarNavAltMarkup">

                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a href="ficha11.html" class="nav-link">Home</a>
                        </li>
                        <li class="divider py-2 d-none d-md-block cor-principal">/</li>
                        <li class="nav-item">
                            <a href="menu.html" id="home" class="nav-link">Menu</a>
                        </li>
                        <li class="divider py-2 d-none d-md-block cor-principal">/</li>
                        <li class="nav-item">
                            <a href="acerca.html" class="nav-link">Acerca</a>
                        </li>
                        <li class="divider py-2 d-none d-md-block cor-principal">/</li>
                        <li class="nav-item pr-3">
                            <a href="contact.html" class="nav-link">Contato</a>
                        </li>
                        <li class="nav-item">
                            <button type="button" class="btn btn-outline-danger" data-toggle="modal" data-target="#reservationmodal">

                                Reservas
                            </button>
                        </li>
                    </ul>
                </div>
            </nav>
            <div class="row public-banner d-none d-md-flex px-3">
                <img class="w-100 h-100" src="http://www.sasuma.pt/portal/img/banner/banner4.png" width="964" height="211" alt="UMa Cantina Banner">
            </div>
        </div>
    </header>
    <br>
    <img src="./assets/logo.png">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <ul>
      <li><a href="https://vuejs.org" target="_blank">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank">Twitter</a></li>
    </ul>
    <h2>Ecosystem</h2>
    <ul>
      <li><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
      <li><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
      <li><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
    </ul>
    <p>pxsdcvg</p>


  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
