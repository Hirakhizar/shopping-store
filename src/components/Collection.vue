<template>
  <section class="wrapper">
    <div class="container">
      <div class="owl-carousel" id="carousel-02">
        <div class="item">
          <img src="/images/4(2).png" alt="Slide 1">
        </div>
        <div class="item">
          <img src="/images/5(2).png" alt="Slide 2">
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* Add styles if needed */
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
      autoplayTimeout: 5000,
      nav: true,
      responsive: {
        0: { items: 1 },
        600: { items: 2 },
        1000: { items: 2 },
      },
    });
  } else {
    console.error("jQuery is not loaded. Check your script paths.");
  }
});
</script>
