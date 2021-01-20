<template>
  <nav class="navbar is-dark" role="navigation" aria-label="main navigation">
    <div class="navbar-brand"> 
      <a class="navbar-logo" href="">
        <img src="~/assets/text-h.svg" class="logo-img">
      </a>
    </div>

    <div id="navbarBasicExample" class="navbar-menu">
      <div class="navbar-start">
      </div>

      <div class="navbar-end">
        <div class="field has-addons">
          <div class="control">
            <input class="input" type="text" placeholder="Find a book">
          </div>
          <div class="control">
            <a href="/" class="button is-info">
              Search
            </a>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {}
</script>
<style scoped>
  .is-dark{
    background-color: indigo;
  }

  .logo-img{
    filter: brightness(0) invert(1);
    width: 180px ;
    height: 40px;
  }

  .navbar-logo{
    padding: 8px 12px;
    margin: 0;
  }

  .navbar-end{
    padding: 8px 12px;
  }
</style>
