<template>
<section class="wrapper">
    <nav class="navbar navbar-expand-lg navbar-light bg-white p-4">
        <div class="container-fluid">
            <!-- Logo -->
            <a class="navbar-brand" href="#">
                <img src="/images/logo.png" width="120" alt="Logo">
            </a>

            <!-- Toggle Button for Mobile -->
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <!-- Navbar Content -->
            <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">HOME<i class="bi bi-caret-down"></i></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">SHOP<i class="bi bi-caret-down"></i></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">PAGES<i class="bi bi-caret-down"></i></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">ABOUT US</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">CONTACT US</a>
                    </li>
                </ul>
            </div>

            <!-- Right Icons -->
            <div class="navbar-icons d-flex align-items-center">
                <a href="#" class="nav-icon"><i class="bi bi-search"></i></a>
                <a href="#" class="nav-icon position-relative">
                    <i class="bi bi-heart fs-4"></i>
                    <span class="position-absolute bottom-0 start-100 translate-middle badge rounded-pill bg-light-red ">
                        1
                    </span>
                </a>
                <a href="#" class="nav-icon position-relative">
                    <i class="bi bi-bag fs-4"></i>
                    <span class="position-absolute bottom-0 start-100 translate-middle badge rounded-pill bg-light-red ">
                        3
                    </span>
                </a>

                <a href="#" class="nav-icon"><i class="fa-solid fa-user"></i></a>
                <a href="#" class="nav-icon"><i class="bi bi-list"></i>
                </a>
            </div>
        </div>
    </nav>
</section>
</template>

  
<style scoped>
.navbar-nav .nav-link {
    font-size: 16px;
    font-weight: 500;
    margin: 0 10px;
    color: #333;
    transition: color 0.3s;
}

.navbar-nav .nav-link:hover {
    color: #007bff;
}

.navbar-icons {
    gap: 15px;
}

.nav-icon {
    color: #333;
    font-size: 18px;
    margin-left: 15px;
    text-decoration: none;
    transition: color 0.3s;
}

.nav-icon:hover {
    color: #007bff;
}
.bg-light-red {
    background-color: #ea4545; /* Very Light Red */
    color:white; /* Darker Red Text */
}
</style>
