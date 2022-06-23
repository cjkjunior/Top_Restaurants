<template>
    <div>
    <Html :lang="dynamic > 50 ? 'en-GB' : 'en_US'">
      <Head>
        <Title>Top 50 Restaurants</Title>
        <Meta name="desc" content="page"/>
        <Link rel="preload" href="https://w7.pngwing.com/pngs/672/907/png-transparent-favicon-buggi-trademark-logo-circle.png" as="script"/>
      </Head>
    </Html>
        <NuxtLayout name="custom">
            <div class="container">
                <RestaurantTable />
            </div>
        </NuxtLayout>
    </div>
</template>