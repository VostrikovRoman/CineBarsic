<template>
  <div class="background" style=''></div>
  <p class="text title">Обо мне</p>
  <div class="card">
    <p class="text">Меня зовут Александр, и я видеограф с трёхлетним опытом работы в сфере видеосъемки. 
Я создаю видео, которые рассказывают вашу историю с уникальным почерком и безупречным качеством.
Я горжусь тем, что моя работа приносит радость и вдохновение другим.
    </p>
    <div class="frame">
      <img class="img" src="./assets/LWy5I99PUns.jpg">
    </div>

  </div>
  <p class="text title">Портфолио</p>
  <p class="text title">Услуги</p>
  
</template>

<script>

</script>

<style>
/*#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}*/
#app{
  font-family: 'TRY Clother';
  font-size: 22px;
  margin: -10px;
}
body{
  overflow-x: hidden;
}
::-webkit-scrollbar {
  width: 0;
  height: 0;
}
.background{
  width: 100vw;
  height: 100vh;
  background-image: url("./assets/LWy5I99PUns.jpg");
  background-size: cover;
  z-index: 1;
  position: fixed;
  margin-top: -25px;
}

.header{
  position: fixed;
  background: #00A4CD;
  width: 101%;
  height: 100px;
  display: none;
}
.card{
  background: #EBEBEB;
  margin: 0px 50px 0px 50px;
  border-radius: 20px;
  box-shadow: 0px 5px 10px #00000080;
  padding: 4vw;
  z-index: 2;
  /* position: fixed; */
}
.text{
  display: inline-block;
  z-index: 2;
}
.title{
  margin-left: auto;
  margin-right: auto;
  font-size: 35px;
  display: block;
}
.img{
  height: 100%;

}
.frame{
  width: 150px;
  height: 150px;
  overflow: hidden;
  border-radius: 100%;
  display: inline-block;
}

@font-face {
	font-family: 'TRY Clother';
	src: url('./assets/fonts/try_clother.eot'); /* IE 9 Compatibility Mode */
	src: url('./assets/fonts/try_clother.eot?#iefix') format('embedded-opentype'), /* IE < 9 */
		url('./assets/fonts/try_clother.woff2') format('woff2'), /* Super Modern Browsers */
		url('./assets/fonts/try_clother.woff') format('woff'), /* Firefox >= 3.6, any other modern browser */
		url('./assets/fonts/try_clother.ttf') format('truetype'), /* Safari, Android, iOS */
		url('./assets/fonts/try_clother.svg#try_clother') format('svg'); /* Chrome < 4, Legacy iOS */
}
@font-face {
	font-family: 'TRY Clother Bold';
	src: url('./assets/fonts/try_clother_bold.eot'); /* IE 9 Compatibility Mode */
	src: url('./assets/fonts/try_clother_bold.eot?#iefix') format('embedded-opentype'), /* IE < 9 */
		url('./assets/fonts/try_clother_bold.woff2') format('woff2'), /* Super Modern Browsers */
		url('./assets/fonts/try_clother_bold.woff') format('woff'), /* Firefox >= 3.6, any other modern browser */
		url('./assets/fonts/try_clother_bold.ttf') format('truetype'), /* Safari, Android, iOS */
		url('./assets/fonts/try_clother_bold.svg#try_clother') format('svg'); /* Chrome < 4, Legacy iOS */
}
</style>
