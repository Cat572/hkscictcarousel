<script>
  import Button from "./Button.svelte";
  import Carousel from "./Carousel.svelte";
</script>

<style>
  main {
    font-family: sans-serif;
    text-align: center;
  }
  .slide-content img {
    height: 50vh;
  }
</style>

<main>
	<h1>Hello Here is some pet</h1>
	<h2>Golden Retriever & Border Collie is Favorite Dogsss
      all varieties cat I Like</h2>
	<Button />
  <br>
  <br>

  <Carousel perPage="1">
  <div class="slide-content">
    <img alt="1" src="https://th-thumbnailer.cdn-si-edu.com/bZAar59Bdm95b057iESytYmmAjI=/1400x1050/filters:focal(594x274:595x275)/https://tf-cmsv2-smithsonianmag-media.s3.amazonaws.com/filer/95/db/95db799b-fddf-4fde-91f3-77024442b92d/egypt_kitty_social.jpg"/>
    </div>
  <div class="slide-content">
    <img alt="2" src="https://www.humanesociety.org/sites/default/files/styles/1240x698/public/2020-07/kitten-510651.jpg?h=f54c7448&itok=ZhplzyJ9"/>
    </div>
  <div class="slide-content">
    <img alt="3" src="https://www.pumpkin.care/dog-breeds/wp-content/uploads/2021/03/BorderCollie-Hero-1-1200x628.png"/>
    </div>
  <div class="slide-content">
    <img alt="4" src="https://www.hypropremium.com.au/wp-content/uploads/2020/03/understand-a-dogs-tail-movements.jpg"/>
    </div>
</Carousel>
</main>