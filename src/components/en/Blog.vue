<template>
    <div class="container-xxl py-5" id="social">
      <div class="container">
        <div class="row g-5">
          <div class="col-lg-4 wow fadeInUp" data-wow-delay="0.1s">
          <div class="h-100">
              <h1 class="display-6 mb-5">
                {{ lang.blog_title }}
              </h1>
              <p class="fs-5 text-dark mb-4 fs-5">
                {{ lang.blog_desc }}
              </p>
              <div class="row g-4 mb-4">
                <div class="d-flex justify-content-center pt-2">
                    <a class="btn border-brownish brownish-icon-svg rounded me-1 " target="_blank" href="https://twitter.com/DamanInfoTech">
                      <i class="fab fa-twitter"></i>
                    </a>
                    <a class="btn border-brownish brownish-icon-svg border-dark rounded me-1" target="_blank" href="https://www.facebook.com/DamanInfoTech">
                      <i class="fab fa-facebook-f"></i>
                    </a>
                    <a class="btn border-brownish brownish-icon-svg border-dark rounded me-1" target="_blank" href="https://www.linkedin.com/company/damn-information-technology/">
                      <i class="fab fa-linkedin-in"></i>
                    </a>
                </div>
              </div>
              
            </div>
          </div>
          <div class="col-lg-8 wow fadeInUp" data-wow-delay="0.5s">
            <a class="twitter-timeline" href="https://twitter.com/DamanInfoTech?ref_src=twsrc%5Etfw">Tweets by DamanInfoTech</a> 
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'EnBlog',
    props: {
      lang: Object,
    }
}
</script>

<style>

</style>
