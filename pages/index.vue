<template>
  <div>
    <NavbarLogin />
    <div class="container">
      <div class="content">
        <img class="logo-img" src="~/assets/logo-text.svg" alt="LiBrainry">
        <div class="links">
          <a
            href="https://github.com/Gabriel-Aragao/librainry-web"
            target="_blank"
            rel="noopener noreferrer"
            class="button is-primary is-outlined"
          >
            GitHub
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavbarLogin from '~/components/NavbarLogin'
export default {
  components: {
    NavbarLogin
  }
}
</script>

<style>

.container {
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: top;
  text-align: center;
  padding-top: 90px;
  background-image: url(../assets/background-05.png);
  background-repeat: no-repeat;
  background-size: 650px;
  background-position: 100% 25%;
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
  padding-top: 150px;
}
</style>
