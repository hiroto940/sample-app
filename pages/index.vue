<template>
  <div class="container">
    <div>
      <Logo/>
      <h1 class="title">
        犬の気持ちになってみろい！！
      </h1>
      <img
        src="https://tv-tokyo.imgix.net/plus/lifestyle/images/akitainu_20200130_00.jpg?auto=format,compress&lossless=0&dpr=1">
     <br>どっちのボタンを押すか選ぶワン！！
      <div class="links">
        <a
          href="https://dogfood8.xsrv.jp/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          おなかすいたワン(笑)
        </a>
        <a
          href="https://travel.rakuten.co.jp/mytrip/amazing/amazingviews
"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          おさんぽいきたいワン！！
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
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
  font-family: 'Quicksand',
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
