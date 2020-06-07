<template>
  <div class="container">
    <div>
      <logo />
      <el-carousel indicator-position="outside">
        <el-carousel-item key="4">
          <img src="~/assets/cover4.jpg" />
        </el-carousel-item>
        <el-carousel-item key="1">
          <img src="~/assets/cover.png" />
        </el-carousel-item>
        <el-carousel-item key="2">
          <img src="~/assets/cover2.png" />
        </el-carousel-item>
        <el-carousel-item key="3">
          <img src="~/assets/cover3.jpg" />
        </el-carousel-item>
      </el-carousel>
      <h1 class="title">
        Coach Celo
      </h1>
      <h2 class="subtitle">
        Aux Passionnées par l'univers de la beauté et de l'esthétique
      </h2>
      <div class="links">
        <a
          href="https://web.facebook.com/The-Celo-Beauty-Boot-Camp-265210257532267/"
          target="_blank"
          class="button--green"
        >
          Facebook
        </a>
        <a
          href="https://www.instagram.com/celokmr/"
          target="_blank"
          class="button--grey"
        >
          Instagram
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
