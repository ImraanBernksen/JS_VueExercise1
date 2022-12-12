<template>
  <nav class="navbar navbar-expand-lg navbar navbar-light bg-dark static-top">
            <div class="container-fluid">
             <img class="navbar-brand" src="https://i.postimg.cc/4dh5mxbv/Volkano-Logo-Transparent.png" alt="logo" height="50">
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                  <li class="nav-item">
                    <a class="nav-link text-white" href="/">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-white" href="/about">About</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-white" href="/contact">Contact</a>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
  <router-view/>
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
