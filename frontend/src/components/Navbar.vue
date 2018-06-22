<template>
  <section class="navbar has-shadow">
    <h1 class="title">Fast Check In</h1>
    <button class="view-event">View Events</button>
  </section>
</template>

<script>
export default {

};
</script>

<style scoped>
.navbar {
  display: flex;
  height: 100%;
  background: var(--primary);
  color: white;
  align-items: center;
  grid-area: nav;
}
.title {
  margin-left: 20px;
}
.view-event {
  margin-left: auto;
  margin-right: 20px;
  background: var(--secondary);
}
</style>
