<template>
  <div>
    <Html :lang="dynamic > 50 ? 'en-GB' : 'en_US'">
      <Head>
        <Title>Restaurantly</Title>
        <Meta name="desc" content="page"/>
        <Link rel="preload" href="https://w7.pngwing.com/pngs/672/907/png-transparent-favicon-buggi-trademark-logo-circle.png" as="script"/>
      </Head>
    </Html>
    <div class="container">
      <h1>Welcome to Restaurantly</h1>
      <a href="/restaurants">Go to restaurants</a>
    </div>
  </div>
</template>

<style scoped>

  .container {
    text-align: center;
    margin-top: 5rem;
  }

</style>
