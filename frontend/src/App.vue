<template>
  <div id="app">
    <Navbar />
    <Home />
  </div>
</template>

<script>
import Home from './components/Home';
import Navbar from './components/Navbar'

export default {
  name: 'Fast Check In',
  components: {
    Home,
    Navbar
  },
};
</script>

<style>
:root {
  --base-background: #b8c2cc;
  --white: #fff;
  --black: #22292f;
  --primary: #3490dc;
  --secondary: #ef5753;
}

html,
body {
  margin: 0;
  font-family: Source Sans Pro, system-ui, -apple-system, BlinkMacSystemFont,
    Segoe UI, Roboto, Oxygen, Ubuntu, Cantarell, Fira Sans, Droid Sans,
    Helvetica Neue;
}

#app {
  display: grid;
  grid-template-columns: 1fr 3fr 1fr;
  grid-template-rows: 0.5fr 5fr;
  grid-template-areas: 'nav nav nav' 'left center right';
  box-sizing: border-box;
  width: 100vw;
  height: 100vh;
  background: var(--base-background);
}

.has-shadow {
  box-shadow: 0 15px 30px 0 rgba(0, 0, 0, 0.11),
    0 5px 15px 0 rgba(0, 0, 0, 0.08);
}
</style>
