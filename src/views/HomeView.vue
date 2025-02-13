<script setup></script>

<template>
<section class="hero-section d-flex align-items-center">
    <div class="overlay">
        <span class="text-white display-3">30% OFF</span>
        <h1 class="hero-title display-1 fw-semibold ">FAVORITE CLOTHING</h1>
        <button class="btn">Get Collection <i class="bi bi-arrow-right-short text-danger w-100"></i></button>
    </div>
</section>
<section class="collections">
    <div class="container">
        <div class="row">
            <!-- Card 1 -->
            <div class="col-md-4">
                <div class="card  text-white">
                    <img class="card-img" src="/images/1.png" alt="Card image">
                    <div class="card-img-overlay  ">
                      <div class="border border-white p-4">
                        <h3 class="card-title">WOMEN </h3>
                        <p class="card-text">Collection</p>
                        <p class="card-text text-dark fw-semibold">view collection</p>
                      </div>
                       
                    </div>
                </div>
            </div>
            <!-- Card 2 -->
            <div class="col-md-4">
                <div class="card  text-white">
                    <img class="card-img" src="/images/2.png" alt="Card image">
                    <div class="card-img-overlay">
                      <div class="border border-white p-4">
                        <h3 class="card-title">MEN </h3>
                        <p class="card-text">Collection</p>
                        <p class="card-text text-dark fw-semibold">view collection</p>
                      </div>
                    </div>
                </div>
            </div>
            <!-- Card 3 -->
            <div class="col-md-4">
                <div class="card  text-white">
                    <img class="card-img" src="/images/3.png" alt="Card image">
                    <div class="card-img-overlay">
                      <div class="border border-white p-4">
                        <h3 class="card-title">KIDS </h3>
                        <p class="card-text">Collection</p>
                        <p class="card-text text-dark fw-semibold">view collection</p>
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
