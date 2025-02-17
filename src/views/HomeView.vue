<script setup></script>

<template>
<section class="hero-section d-flex align-items-center">
    <div class="overlay">
        <span class="text-white display-3">30% OFF</span>
        <h1 class="hero-title display-1  ">FAVORITE CLOTHING</h1>
        <button class="btn">Get Collection <i class="bi bi-arrow-right-short text-danger w-100"></i></button>
    </div>
</section>


<section class="collections py-4 py-md-">
    <div class="container">
        <div class="row g-4"> <!-- Added gap between columns -->
            <!-- Card 1 -->
            <div class="col-lg-4 col-md-6 col-sm-12">
                <div class="card text-white position-relative overflow-hidden">
                    <img class="card-img img-fluid" src="/images/1.png" alt="Card image">
                    <div class="card-img-overlay d-flex justify-content-start align-items-center">
                        <div class="border border-white p-3 p-md-4 p-sm-3 p-lg-5 w-100 h-100"> <!-- Adjust padding -->
                            <h3 class="card-title fw-bold fs-5 fs-md-4 fs-lg-3">WOMEN</h3>
                            <p class="card-text fs-6 fs-md-5">Collection</p>
                            <p class="card-text text-dark fw-semibold fs-6 fs-md-5">View Collection</p>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Card 2 -->
            <div class="col-lg-4 col-md-6 col-sm-12">
                <div class="card text-white position-relative overflow-hidden">
                    <img class="card-img img-fluid" src="/images/2.png" alt="Card image">
                    <div class="card-img-overlay d-flex justify-content-start align-items-center">
                        <div class="border border-white p-3 p-md-4 p-lg-5 w-100 h-100">
                            <h3 class="card-title fw-bold fs-5 fs-md-4 fs-lg-3">MEN</h3>
                            <p class="card-text fs-6 fs-md-5">Collection</p>
                            <p class="card-text text-dark fw-semibold fs-6 fs-md-5">View Collection</p>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Card 3 -->
            <div class="col-lg-4 col-md-6 col-sm-12">
                <div class="card text-white position-relative overflow-hidden">
                    <img class="card-img img-fluid" src="/images/3.png" alt="Card image">
                    <div class="card-img-overlay d-flex justify-content-start align-items-center">
                        <div class="border border-white p-3 p-md-4 p-lg-5 w-100 h-100">
                            <h3 class="card-title fw-bold fs-5 fs-md-4 fs-lg-3">KIDS</h3>
                            <p class="card-text fs-6 fs-md-5">Collection</p>
                            <p class="card-text text-dark fw-semibold fs-6 fs-md-5">View Collection</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>


</template>

<style scoped>
/* Hero Section */
.hero-section {
    background: url('/images/11.png') no-repeat center center/cover;
    height: 100vh;
    /* Adjust the height */
    position: relative;
}

.overlay {
    /* Dark overlay */
    padding-left: 5%;

}

.hero-title {

    color: rgb(50, 47, 47);
}

/* Button */
.btn {
    background: white;
    color: black;

    padding: 12px 35px;
    font-size: 1.2rem;
    cursor: pointer;
    transition: 0.3s;

}

.collections {
    margin: 5rem;
}

.btn:hover {
    background: #e85b50;
    color: aliceblue;
}
.btn i:hover{
    color:aliceblue;
}
</style>
