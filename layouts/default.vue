<template>
  <div>
    <div id="navbar">
      <div class="navbar-links">
        <nuxt-link class="button--white" to="/"> Home </nuxt-link>
        <nuxt-link class="button--white" to="/videos"> Ayame-Momo ビデオデモ </nuxt-link>
      </div>
    </div>
    <div id="default-body">
      <Nuxt />
    </div>
  </div>
</template>

<style>
#navbar {
  height: 70px;
  width: 100%;
  background-color: #313b46;
}

#navbar .navbar-links {
  max-width: 800px;
  margin: auto;
}

#navbar a {
  margin: 10px;
  font-size: 20px;
}
#default-body {
  max-width: 800px;
  margin: auto;
}

html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--white {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #fff;
  color: #fff;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--white:hover {
  color: #35495e;
  background-color: #fff;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
