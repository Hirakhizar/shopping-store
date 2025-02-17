<script setup>
import HomeView from './views/HomeView.vue';
import TopBar from './components/TopBar.vue';
import NavBar from './components/NavBar.vue';
import NewArrivals from './components/NewArrivals.vue';
import TrandingNow from './components/TrandingNow.vue';
import Collection from './components/Collection.vue';
import LatestArivals from './components/LatestArivals.vue';
import SaleImage from './components/SaleImage.vue';
import Subscription from './components/Subscription.vue';
import FollowUs from './components/FollowUs.vue';
import FooterComp from './components/FooterComp.vue';
import SliderTwo from './components/SliderTwo.vue';


</script>

<template>

    <div class="wrapper">
      <TopBar />
      <NavBar />
     <HomeView /> 
     <NewArrivals />
     <TrandingNow />
     <Collection />
    
     <SaleImage />
     <LatestArivals />
     <SliderTwo />
     <Subscription />
     <FollowUs />
     <FooterComp />
    
    </div>
  

</template>


