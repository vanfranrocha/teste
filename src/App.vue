<template>
  <div id="app">

    <b-container class="bv-example-row">
        <b-row align-h="center" align-v="center" class="p-3" style="height: -webkit-fill-available;">
            <b-col align="right" sm="12" lg="3">
              <b-navbar vertical type="white" toggleable>
                <b-navbar-toggle target="nav_dropdown_collapse"></b-navbar-toggle>
                <!-- <b-navbar-brand>  <img src="./assets/logo.png"></b-navbar-brand> -->
                <b-collapse  is-nav id="nav_dropdown_collapse">
                  <b-nav vertical class="w-25">
                    <b-nav-item active>Active</b-nav-item>
                    <b-nav-item>Link</b-nav-item>
                    <b-nav-item>Another Link</b-nav-item>
                    <b-nav-item disabled>Disabled</b-nav-item>
                  </b-nav>
                </b-collapse>
              </b-navbar>
            </b-col>
            <b-col sm="12" align="left"  lg="9">
              <h1>{{ msg }}</h1>
              <p>Olá, sou a Vanessa Rocha, estudante, designer, programadora, católica, amo minha família e amo viajar.<br><br>
                Trabalho profissionalmente com design desde 2016, e desde então busco aprimorar e adquirir cada vez mais conhecimento. Hoje estou cada vez mais em busca de novas oportunidades e projetos, acredito nos pequenos e sonho em torná-los grande. Me conte seu novo projeto, entre em contato comigo e vamos conversar.</p>
            </b-col>
        </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Vanessa'
    }
  }
}
</script>

<style>
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
