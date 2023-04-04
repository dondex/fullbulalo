<template>
    <div id="main">
        <!-- ======= About Section ======= -->
        <About />
        <!-- End About Section -->


        <!-- menu section -->
        <!-- <Menu/> -->
        <!--end  menu section -->


        <!-- ======= Book A Table Section ======= -->
        <MyReservation/>
        <!-- End Book A Table Section -->

        <!-- ======= Testimonials Section ======= -->
        <Testimonial/>
        <!-- End Testimonials Section -->

        <!-- ======= Gallery Section ======= -->
        <!-- <Gallery /> -->
        <!-- ======= END Gallery Section ======= -->



        <!-- ======= Contact Section ======= -->
        <section id="contact" class="contact">

        <div class="container" data-aos="fade-up">

            <div class="row mt-5 ">

            <div class="col-lg-5 d-flex align-items-stretch ">
                <div class="info">
                <div class="address">
                  <h4>Location:</h4>
                  <p>bulalohan sa riyadh, Sulimaniya area near Military hospital , Riyadh, Saudi Arabia</p>
                </div>
                  <div class="email">
                    <h4>Email:</h4>
                    <p>ronald@bulalohansariyadh.xyz</p>
                  </div>
                  <div class="phone">
                    <h4>Contact:</h4>
                    <p>
                      <ul>
                        <li>0569663285</li>
                        <li>0570769407</li>
                      </ul>
                    </p>
                  </div>
                  <iframe src="https://maps.google.com/maps?q=bulalohan sa riyadh, Sulimaniya area near Military hospital , Riyadh, Saudi Arabia&t=&z=10&ie=UTF8&iwloc=&output=embed" frameborder="0" style="border:0; width: 100%; height: 290px;" allowfullscreen></iframe>
              </div>

            </div>

            <div class="col-lg-7 mt-5 mt-lg-0 d-flex align-items-stretch">

                <Inquiry/>

            </div>

            </div>

        </div>
        </section>

        <!-- End Contact Section -->
    </div>
</template>

<script>
import Testimonial from '../components/Testimonial.vue';
import Gallery from '../components/Gallery.vue';
import MyReservation from '../components/MyReservation.vue';
import Menu from '../components/Menu.vue';
import Inquiry from '../components/Inquiry.vue';
import About from '../components/About.vue';





export default {
    name: 'Home',
    components: {
        Testimonial,
        Gallery,
        MyReservation,
        Menu,
        Inquiry,
        About
    }
}
</script>
