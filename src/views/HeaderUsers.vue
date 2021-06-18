<template>
  <div>
    <h2>Users</h2>
    <nav style="width: 700px; margin: auto; padding-top: 50px;">
      <router-link to="/" active-class="link--active" exact class="link">home</router-link>
      <router-link to="/users" active-class="link--active" exact class="link">users</router-link>
    </nav>
  </div>
</template>

<style scoped>
.link {
  margin-right: 10px;
}
.link--active {
font-size: 20px;
}
</style>