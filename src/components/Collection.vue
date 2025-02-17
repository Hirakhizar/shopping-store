<template>
  <section class="wrapper slider-wrapper">
    <div class="container">
      <div class="owl-carousel" id="carousel-02">
        <div class="item d-flex align-items-center justify-content-center flex-column" style="background-image: url('public/images/4(2).png');">
          <h5 class="display-6 text-dark">FASHION CLOTHING</h5>
          <button class="btn rounded-0  shop-btn">SHOP Now <i class="bi bi-arrow-right-short  text-dark  "></i></button>
        </div>
        <div class="item d-flex align-items-center justify-content-center flex-column" style="background-image: url('public/images/5(2).png');">
          <h5 class="display-6 text-dark">FASHION CLOTHING</h5>
          <button class="btn rounded-0   shop-btn">SHOP Now <i class="bi bi-arrow-right-short  text-dark  "></i></button>
        </div>
      </div>
    </div>
  </section>
 
</template>

<style type="stylesheet" scoped>

.slider-wrapper .owl-carousel .owl-dots.disabled {

  display: block !important; 
     margin: 50px;
    height: 5px;
    width: 40px;
    background-color: black;

}
.slider-wrapper .item {
background-size: cover;
background-position:center ;
width: 100%;
height: 400px;
}

.shop-btn{
  background-color: rgb(252, 254, 255);
 }


</style>

<script setup>
import { onMounted } from "vue";



onMounted(() => {
  // Ensure jQuery is loaded before initializing Owl Carousel
  if (window.jQuery) {
    $("#carousel-02").owlCarousel({
      loop: true,
      margin: 10,
      autoplay: true,
      autoplayTimeout: 2000,
      nav: false,
      dots: true, 

      responsive: {
        0: { items: 1 },
        600: { items: 1 },
        1000: { items:2 },
      },
    });
  }
});
</script>
