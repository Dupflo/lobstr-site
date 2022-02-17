<template>
  <header>
    <nav class="topbar">
      <Logo />
      <div class="section">
        <a href="#"> Store </a>
        <a href="#"> Pricing </a>
        <a href="#"> Blog </a>
      </div>
      <BaseButton>Sign in</BaseButton>
    </nav>
  </header>
</template>

<script>
import Button from "./Base/Button.vue";
export default {
  components: { Button },
};
</script>

<style></style>
