<template>
  <main class="w-full md:w-2/3 lg:w-3/4">
    <header>
      <NuxtLink to="/">
        <img src="/main.png" class="w-36" alt="logo">
      </NuxtLink>
    </header>
  </main>
</template>
<style>
body {
  background: url('/bg.gif');
  background-size: cover;
  display: flex;
  justify-content: center;
  padding: 3rem 0;
}
* {
  box-sizing: border-box;
}
</style>