<template>
    <div class="container-fluid p-0 mb-5 wow fadeIn" data-wow-delay="0.1s">
      <div id="header-carousel" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img class="w-100" src="@/assets/img/slider_2.png" alt="Image" />
            <div class="carousel-caption">
              <div class="container">
                <div class="row">
                  <div class="col-12 col-lg-6 ms-5">
                    <h1 class="display-3 text-dark mb-4 animated slideInDown">
                      {{ lang.slider_1_title }}
                    </h1>
                    <h2 class="fs-5 text-dark mb-5">
                      {{ lang.slider_1_desc }}
                    </h2>
                    <!-- <a href="" class="btn btn-primary py-3 px-5">More Details</a> -->
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <img class="w-100" src="@/assets/img/slider_1.png" alt="Image" />
            <div class="carousel-caption">
              <div class="container">
                <div class="row">
                  <div class="col-12 col-lg-6 ms-5">
                    <h1 class="display-3 text-dark mb-4 animated slideInDown">
                      {{ lang.slider_2_title }}
                    </h1>
                    <h2 class="fs-5 text-dark mb-5">
                      {{ lang.slider_2_desc }}
                    </h2>
                    <!-- <a href="" class="btn btn-primary py-3 px-5">More Details</a> -->
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#header-carousel"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#header-carousel"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
</template>

<script>
export default {
    name: 'EnCarousel',
    props: {
      lang: Object,
    }
}
</script>
