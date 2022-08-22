<template>

<div>
    <!-- Spinner Start -->
    <div
      id="spinner"
      class="bg-white position-fixed translate-middle w-100 vh-100 top-50 start-50 d-flex align-items-center justify-content-center"
      :class="isLoading ? 'show' : ''"
    >
      <div class="spinner-grow text-primary" role="status"></div>
    </div>
    <!-- Spinner End -->
    
    <!-- Topbar Start -->
    <top-bar :lang="lang" />
    <!-- Topbar End -->

    <!-- Navbar Start -->
    <en-navbar :lang="lang" />
    <!-- Navbar End -->

    <!-- Carousel Start -->
    <en-carousel :lang="lang" />
    <!-- Carousel End -->

    <!-- About Start -->
    <en-about :lang="lang" />
    <!-- About End -->

    <!-- Vision Start -->
    <en-vision :lang="lang" />
    <!-- Vision End -->

    <!-- Features Start -->
    <en-features :lang="lang" />
    <!-- Features End -->

    <!-- Service Start -->
    <en-services :lang="lang" />
    <!-- Service End -->

    <!-- Appointment Start -->
    <en-appointment :lang="lang" />
    <!-- Appointment End -->

    <!-- Twitter Feed -->
    <en-blog :lang="lang"/>
    <!-- End Twitter Feed-->

    <!-- Footer Start -->
    <en-footer :lang="lang" />
    <!-- Footer End -->

    <!-- Back to Top -->
    <a href="#" class="btn btn-lg btn-primary btn-lg-square back-to-top">
      <i class="bi bi-arrow-up"></i>
    </a>
</div>
  
</template>

<script>
/**
 * 
 * Language Importing
 * 
 * */

import lang from '@/lang/en';

/**
 * 
 * End Language Importing
 * 
 * */

/**
 * 
 * English Components
 * 
 * */
import TopBar from '@/components/unified/TopBar.vue'
import EnNavbar from '@/components/en/Navbar.vue';
import EnCarousel from '@/components/en/Carousel.vue';
import EnAbout from '@/components/en/About.vue';
import EnVision from '@/components/en/Vision.vue';
import EnFooter from '@/components/en/Footer.vue';
import EnAppointment from '@/components/en/Appointment.vue';
import EnServices from '@/components/en/Services.vue';
import EnFeatures from '@/components/en/Features.vue';
import EnBlog from '@/components/en/Blog.vue';


/**
 * 
 * Arabic Components
 * 
 * */

export default {
  name: 'App',
  components: {
    TopBar,
    // English Components
    EnNavbar, EnCarousel, EnAbout, EnVision, EnFooter, EnAppointment, EnServices, EnFeatures, EnBlog
    // Arabic Components
  },   

  data(){
    return {
      lang: lang,
      isLoading: true,
    }
  },
  mounted(){
      setTimeout(() => {
        this.isLoading = false
      }, 3000);
  },
}
</script>

