<template>
  <div id="app">
    
      <nav class="navbar navbar-expand navbar-dark bg-dark">
          <div class="nav navbar-nav">
              <router-link to="/" class="nav-item nav-link active">Home </router-link>
              <router-link to="/about" class="nav-item nav-link">About</router-link>
              <router-link to="/employees" class="nav-item nav-link">employees</router-link>
          </div>
      </nav>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #b49301;
}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #502c2c;
}

#nav a.router-link-exact-active {
  color: #99b942;
}
</style>
