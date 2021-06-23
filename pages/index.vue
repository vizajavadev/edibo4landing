<template xmlns="http://www.w3.org/1999/html">
  <div class="container">
<!--    <div>-->
<!--    <h1>Hello Nuxt!</h1>-->
<!--    </div>-->
<!--    <div class="button&#45;&#45;green"">-->
<!--    <nuxt-link to="/users" >Users</nuxt-link>-->
<!--  </div>-->
<!--  </div>-->


<!--              <a-->
<!--                href="https://nuxtjs.org/"-->
<!--                target="_blank"-->
<!--                rel="noopener noreferrer"-->
<!--                class="button&#45;&#45;green"-->
<!--              >-->
<!--                Users-->
<!--              </a>-->



    <div>
      <Logo />
      <h1 class="title">
      EDIBO 4
      </h1>

      <div class="links">


<!--        <nuxt-link to="/products" class="button&#45;&#45;grey" >Videos</nuxt-link>-->
        <!--        <a-->
        <!--          href="/users"-->
        <!--          target="_blank"-->
        <!--          rel="noopener noreferrer"-->
        <!--          class="button&#45;&#45;green"-->
        <!--        >-->
        <!--          Users-->
        <!--        </a>-->
<!--        <a-->
<!--          href="https://github.com/nuxt/nuxt.js"-->
<!--          target="_blank"-->
<!--          rel="noopener noreferrer"-->
<!--          class="button&#45;&#45;grey"-->
<!--        >-->
<!--          GitHub-->
<!--        </a>-->
      </div>

      <div class="links">
<!--            <nuxt-link to="/users" class="button&#45;&#45;green" >Users</nuxt-link>-->
<!--        <nuxt-link to="/products" class="button&#45;&#45;grey" >Slides</nuxt-link>-->

<!--        <a-->
<!--          href="/users"-->
<!--          target="_blank"-->
<!--          rel="noopener noreferrer"-->
<!--          class="button&#45;&#45;green"-->
<!--        >-->
<!--          Users-->
<!--        </a>-->

      </div>
      <div class="grid-container">
        <div class="item1">
          <nuxt-link to="/users" class="button--grey" >Users</nuxt-link>
        </div>
        <div class="item2">
          <nuxt-link to="/products" class="button--grey" >Slides</nuxt-link>
        </div>
        <div class="item3">
          <nuxt-link to="/videos" class="button--grey" >Videos</nuxt-link>
        </div>
        <div class="item4">        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a></div>

      </div>
    </div>


      </div>
</template>

<script>
export default {}
</script>

<style>


.grid-container {
  display: grid;
  grid-template-columns: auto auto ;
  grid-template-rows: auto auto;
  grid-gap: 10px;
  background-color: #3b8070;
  padding: 10px;
}

.grid-container > div {
  background-color: rgba(255, 255, 255, 0.2);
  text-align: center;
  padding: 20px 0;
  font-size: 30px;
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
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
  padding-top: 15px;
}
</style>
