<template>
  <div>
    <h1>Welcome to the homepage</h1>
    <section>
    <p class="primary">This page will be displayed at the / route.</p>
  </section>

    <AppAlert>
      This is an auto-imported component
      <img src="/img/icon-green.png" alt="Nuxt3 Logo from Public Resource" />
      <img src="~/assets/img/icon-green.png" alt="Nuxt3 Logo from " />
    </AppAlert>
  </div>
</template>

<style lang="scss" scoped>
.primary {
  color: $primary;
}
</style>