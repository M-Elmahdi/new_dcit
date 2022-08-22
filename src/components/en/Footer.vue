<template>
    <div
      class="container-fluid bg-dark footer pt-5 wow fadeIn"
      data-wow-delay="0.1s"
    >
      <div class="container py-5">
        <div class="row g-5">
          <div class="col-lg-3 col-md-6">
            <h1 class="text-white mb-4">
              <img
                width="150"
                height="150"
                class="img-fluid me-3"
                src="@/assets/identity/white_logo.png"
              />
            </h1>
            <p>
              {{ lang.slider_2_desc }}
            </p>
            <div class="d-flex pt-2">
              <a class="btn btn-square me-1" target="_blank" href="https://twitter.com/DamanInfoTech"
                ><i class="fab fa-twitter"></i
              ></a>
              <a class="btn btn-square me-1" target="_blank" href="https://www.facebook.com/DamanInfoTech"
                ><i class="fab fa-facebook-f"></i
              ></a>
              <a class="btn btn-square me-0" target="_blank" href="https://www.linkedin.com/company/damn-information-technology/"
                ><i class="fab fa-linkedin-in"></i
              ></a>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <h5 class="text-light mb-4">Address</h5>
            <p>
              <i class="fa fa-map-marker-alt me-3"></i>{{ lang.company_address }}
            </p>
            <p><i class="fa fa-phone-alt me-3"></i>{{ lang.phone_number }}</p>
            <p><i class="fa fa-envelope me-3"></i>info@dcit.ly</p>
          </div>
          <div class="col-lg-3 col-md-6">
            <h5 class="text-light mb-4">Quick Links</h5>
            <a class="btn btn-link" href="#about">About</a>
            <a class="btn btn-link" href="#vision">Vision</a>
            <a class="btn btn-link" href="#values">Values</a>
            <a class="btn btn-link" href="#services">Services</a>
            <a class="btn btn-link" href="#social">News</a>
            <a class="btn btn-link" href="#contactus">Contact Us</a>
            
          </div>
          <!-- <div class="col-lg-3 col-md-6">
            <h5 class="text-light mb-4">Register As A Supplier</h5>
            <p>Dolor amet sit justo amet elitr clita ipsum elitr est.</p>
            <div class="position-relative mx-auto" style="max-width: 400px">
              <a href="" class="btn btn-primary px-3 ms-auto ">Register as Supplier</a>
            </div>
          </div> -->
        </div>
      </div>
      <div class="container-fluid copyright">
        <div class="container">
          <div class="row">
            <div class="col-md-6 text-center text-md-start mb-3 mb-md-0">
              &copy; <a href="#">{{ lang.company_name }}</a>, All Right Reserved.
            </div>
            <!-- <div class="col-md-6 text-center text-body text-sm text-md-end">
              Designed By HTML Codex
              <br />Distributed By:
              ThemeWagon
            </div> -->
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'EnFooter',
    props: {
      lang: Object,
    }
}
</script>

<style>

</style>
