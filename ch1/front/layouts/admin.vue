<template>
  <div>
    <nav>
      <nuxt-link to="/">HOME</nuxt-link>
      <nuxt-link to="/profile">PROFILE</nuxt-link>
      <nuxt-link to="/signup">SIGNUP</nuxt-link>
      <nuxt-link to="/admin">ADMIN</nuxt-link>
    </nav>
    <!-- 이 안에 pages에 구현된 page component 가 그려진다. -->
    <nuxt />
  </div>
</template>

<script>
export default {};
</script>

<style></style>
