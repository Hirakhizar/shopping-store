<template>
<section class="slider-wrapper my-5">
    <div class="container">
    <div class="owl-carousel border-top border-bottom p-5 " id="carousel-01">
        <div class="item">
            <img src="/images/brand1.png" width="25" height="auto" alt="Brand 1">
        </div>
        <div class="item">
            <img src="/images/brand2.png"  alt="Brand 2">
        </div>
        <div class="item">
            <img src="/images/brand3.png"  alt="Brand 3">
        </div>
        <div class="item">
            <img src="/images/brand4.png"  alt="Brand 4">
        </div>
        <div class="item">
            <img src="/images/brand5.png"  alt="Brand 5">
        </div>
        <div class="item">
            <img src="/images/brand6.png"  alt="Brand 6">
        </div>
    </div>
</div>

</section>
</template>

<style type="stylesheet" scoped>
.slider-wrapper .item img {
background-size: cover;
background-position:center ;
width: 50%;
height: 100px;
}

.owl-carousel .owl-nav.disabled
 {
    display: block !important;
   }


   .owl-carousel .owl-nav button {
  background-color: #333; /* Dark background */
  color: #fff; /* White text */
  padding: 10px 15px;
  font-size: 18px;
  border-radius: 5px;
  border: none;
  cursor: pointer;
}

.owl-carousel .owl-nav button:hover {
  background-color: #555;
}

.owl-carousel .owl-nav.disabled{
    display: block !important;
}

.owl-carousel .owl-nav .owl-prev, 
.owl-carousel .owl-nav .owl-next {
  background-size: cover;
  width: 40px; 
  height: 40px;
  display: block;
  background-repeat: no-repeat;
}

.owl-carousel .owl-nav .owl-prev {
  background-image: url('public/images/arrowLeft.png') !important;
}

.owl-carousel .owl-nav .owl-next {
  background-image: url('public/images/arrowRight.png');
}


</style>
<script setup>
import { onMounted } from "vue";

onMounted(() => {
  // Ensure jQuery is loaded before initializing Owl Carousel
  if (window.jQuery) {
    $("#carousel-01").owlCarousel({
      loop: true,
      margin: 10,
      autoplay: true,
      autoplayTimeout: 2000,
      nav: false,
      dots: true, 

      responsive: {
        0: { items: 2 },
        600: { items: 3 },
        1000: { items:6 },
      },
    });
  }
});
</script>
