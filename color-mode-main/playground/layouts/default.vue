<template>
  <div class="container">
    <Meta
      name="description"
      content="Demo of using @nuxtjs/color-mode for Nuxt, supporting dark mode and custom colors"
    />
    <p>
      <NuxtLogo />
    </p>
    <slot />
    <p class="note">
      Demo based on <a href="https://color-mode.nuxtjs.org">@nuxtjs/color-mode</a> module.
    </p>
  </div>
</template>

<style>
p {
  padding: 20px 0;
  margin: 0;
}
.container {
  text-align: center;
  padding: 50px;
}
.note {
  transition: all .3s;
  display: inline-block;
  padding: 15px 15px;
  border-radius: 5px;
  background-color: var(--bg-secondary);
  color: var(--color-secondary);
}
</style>
