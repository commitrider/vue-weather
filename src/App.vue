<script setup>

</script>

<template>
  <body>
    <main>
      <div class="card">
        <div class="header">
          <input class="input" type="text" placeholder="Write city">
          <button class="search">Search</button>
        </div>
        <div class="country">Ukraine</div>
        <div class="card_blocks">
          <div class="card_block-left">
            <div class="image"><img src="" alt="weather"></div>
          </div>
          <div class="card_block-right">
            <div class="type_weather">Partly Cloudy</div>
            <div class="day">Friday</div>
            <div class="temperature">28&deg</div>
          </div>
        </div>
      </div>
    </main>
  </body>
</template>

<style scoped lang="scss">
@import'./assets/scss/main.scss';
</style>
