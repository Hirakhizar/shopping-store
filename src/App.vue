<script setup>
import HomeView from './views/HomeView.vue';
import TopBar from './components/TopBar.vue';
import NavBar from './components/NavBar.vue';
import NewArrivals from './components/NewArrivals.vue';
import TrandingNow from './components/TrandingNow.vue';
import Collection from './components/Collection.vue';
import LatestArivals from './components/LatestArivals.vue';


</script>

<template>

    <div class="wrapper">
      <TopBar />
      <NavBar />
     <HomeView /> 
     <NewArrivals />
     <TrandingNow />
     <Collection />
     <LatestArivals />
    </div>
  

</template>


