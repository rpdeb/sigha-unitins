<template>
  <div id="app">
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="#">SIGHA</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">SALAS</b-nav-item>
          <b-nav-item href="#" >HORARIO</b-nav-item>
             <b-nav-item href="#" >SEMESTRES</b-nav-item>
                <b-nav-item href="#" >PERIODO</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>

    <table class="table caption-top">
      <caption>
        <center>
      TABELA DE HORARIOS
      </center>
      </caption>
      <thead>
        <tr>
          <th scope="col">PERIODO</th>
          <th scope="col">SEMESTRE</th>
          <th scope="col">HORARIO</th>
          <th scope="col">SALAS</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">1º</th>
          <td>2020/1</td>
          <td>10:30</td>
          <td>BLOCO C SALA 10</td>
        </tr>
        <tr>
          <th scope="row">2º</th>
          <td>2020/2</td>
          <td>11:00</td>
          <td>LABIN 1 </td>
        </tr>
        <tr>
          <th scope="row">3º</th>
          <td>2021/1</td>
          <td>12:00</td>
          <td>LABIN 2</td>
        </tr>
      </tbody>
    </table>
  </div>
  <!-- <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <router-view/>
    <div> -->
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

</style>
