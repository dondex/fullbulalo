<template>
    <div>
            <header>
                <nav class="navbar navbar-expand-lg nabar-theme py-0 fixed-top">
                    <div class="container">
                        <a class="navbar-brand" href="./index.html">
                            <img class="img-fluid logo" src="../../img/logo_3.png" alt=""/>
                        </a>
                        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                            <span class="navbar-toggler-icon"></span>
                        </button>
                        <div class="collapse navbar-collapse" id="navbarSupportedContent">
                            <ul class="navbar-nav ms-auto my-2 mb-lg-0">
                            <li class="nav-item">
                                <a class="btn btn-link text-black mx-2 btn-lg" href="./index.html" type="submit">Home</a>
                            </li>
                            <li class="nav-item">
                                <a class="btn btn-link text-black mx-2 btn-lg" href="./menu.html" type="submit">Menu</a>
                            </li>
                            <li class="nav-item">
                                <a class="btn btn-link text-black mx-2 btn-lg" href="#bookTable" type="submit">Book Now</a>
                            </li>
                            </ul>
                        </div>
                    </div>
                </nav>
            </header>

            <!-- ======= Hero Section ======= -->
            <Hero/>
            <!-- End Hero -->
    </div>
</template>

<script >
import Hero from './Hero.vue';


export default {
    name: 'Navbar',
    components: {
        Hero
    }
}


</script>
