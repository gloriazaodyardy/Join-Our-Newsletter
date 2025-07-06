<script setup>
</script>

<template>
  <header></header>
  <main class="flex-center gap-5 text-center">
    <div class="flex-center gap-3">
      <img src="../resources/logo.svg" alt="logo" />
      <h1 class="heading black">Join our newsletter</h1>
      <p class="subheading text-gray-600">Keep up with our latest collections, exclusive deals, and special offers! We
        introduce a new collection every
        week, so stay tuned to snag the hottest items just for you.</p>
    </div>
    <form class="flex-center m-auto p-4 rounded-4 gap-4 shadow bg-white"
      style="width: clamp(17rem, 65vw, 33rem);">
      <input type="email" class="form-control placeholder-text bg-gray-100 p-3" id="email" aria-describedby="email"
        placeholder="Enter your email address">
      <button type="submit" class="btn btn-primary w-100 button-text p-3">Subscribe now</button>
      <div class="helper-text text-start text-gray-600">Your email is 100% confidential and won’t send you any spam.
      </div>
    </form>
  </main>
  <footer class="text-center mt-5">
    <p>
      Coded by <a href="#">Gloriaza</a> | Challenge by
      <a href="https://www.devchallenges.io?ref=challenge" target="_blank">devChallenges.io</a>.
    </p>
  </footer>
</template>

<style scoped>
input::placeholder {
  text-align: center;
  color: var(--bs-secondary);
}
</style>