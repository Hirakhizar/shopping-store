<template>
<section class="subscription-wrapper my-5">
    <div class="container">
        <div class="row bg-secondary opacity-75 p-5 text-white d-flex flex-column justify-content-center align-items-center text-center">
            <div class="col-lg-6 py-4">
                <p class="display-6">KEEP CONNECTED</p>
                <p>___________________</p>
                <p>Get updates by subscrib our weekly newsletters </p>
            </div>

            <div class="col-lg-6 py-3">
                <div class="input-group position-relative">
                    <span class="input-group-text bg-secondary border-top-0 border-start-0 border-end-0 rounded-0">
                        <i class="bi bi-envelope text-white"></i>
                    </span>
                    <input type="email" class="form-control placeholder-white bg-secondary border-top-0 border-start-0 border-end-0 rounded-0 text-white" placeholder="Email Address">
                    <span class="position-absolute subscribe-text ">Subscribe</span>
                </div>
            </div>
        </div>
    </div>
</section>
<section class="service text-center p-5 my-5">
    <div class="container">
        <div class=" border-top border-bottom p-3">
        <div class="row ">
            <div class="col-lg-4 border-end ">
                <p>
                    <i class="bi bi-truck text-danger fs-1 opacity-75"></i>
                </p>
               
                   <h6> FREE SHIPPING,RETURN</h6>
               
                <p class="text-secondary">
                   Free Shipping On All Orders 
                </p>
            </div>
            <div class="col-lg-4 border-end  ">
                <p>
                    <i class="bi bi-cash-stack text-danger fs-1 opacity-75"></i>
                </p>
               
                   <h6> MONEY BACK GUARANTEE</h6>
               
                <p class="text-secondary">
                   30 Days Money Back Guarantee
                </p>
            </div>
            <div class="col-lg-4">
                <p>
                    <i class="bi bi-headset text-danger fs-1 opacity-75"></i>
                </p>
               
                   <h6> 1-800-33-44-55</h6>
               
                <p class="text-secondary">
                  24/7 Days Support
                </p>
            </div>
        </div>
    </div>
    </div>
</section>
</template>

<style scoped>
.placeholder-white::placeholder {
    color: white !important;
    /* Makes placeholder text white */
    opacity: 1;
    /* Ensures full opacity */
}
.subscribe-text {
      right: 10px;
      top: 20%;

      
      padding: 5px 10px;
    
  }
</style>
