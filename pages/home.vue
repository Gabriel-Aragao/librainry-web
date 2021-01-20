<template>
  <div>
    <NavbarHome />
    <div class="container">
      <div class="content">
        <h1 class="title"> You have no books in your shelf! </h1>
        <h3 class="subtitle"> Find one above. </h3>
        <div class="links">

        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavbarHome from '~/components/NavbarHome'
export default {
  components: {
    NavbarHome
  }
}
</script>

<style scoped >

.container {
  margin: 0 auto;
  display: flex;
  height: 90vh;
  justify-content: center;
  align-items: top;
  text-align: center;
  padding-top: 90px;
  background-image: url(../assets/background-home-05.png);
  background-repeat: no-repeat;
  background-size: 800px;
  background-position: 50% 60%;
}

.logo-img{
  height: 250px;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 50px;
  color: #4B0082;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 20px;
  color: #4B0082;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 150px;
}
</style>
