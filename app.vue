<template>
  <div>
    <NuxtLayout>
      <NuxtPage class="site-content"/>
    </NuxtLayout>
  </div>
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400&display=swap');
:root {
  --col-primary: black;
  --col-secondary: white;
}
html, body {
  margin: 0px;
}
.site-content{
  margin-top: 49px;
  padding: 50px 15%;
}
*{
  font-family: 'Montserrat', sans-serif;
}
</style>