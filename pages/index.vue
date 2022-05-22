<template>
  <div>
    <Html :lang="dynamic > 50 ? 'en-GB' : 'en-US'">
      <Head>
        <Title> Restaurant </Title>
        <Meta name="description" content="my page is cool" />
        <Link
          rel="preload"
          href="https://www.iconpacks.net/icons/2/free-sad-face-icon-2691-thumb.png"
          as="script"
        />
      </Head>
    </Html>
    <div class="container">
      <h1>Welcome to restaurant</h1>
      <NuxtLink to="/restaurant"> Go to restaurants </NuxtLink>
    </div>
  </div>
</template>

<style scoped>
.container {
  text-align: center;
  margin-top: 2rem;
}
</style>