<template>
    <div class="container-xxl py-5" id="about">
      <div class="container">
        <div class="row g-5">
          <div class="col-lg-6 wow fadeInUp" data-wow-delay="0.1s">
            <div
              class="position-relative overflow-hidden rounded ps-5 pt-5 h-100"
              style="min-height: 400px"
            >
              <img
                class="position-absolute w-100 h-100"
                src="@/assets/icons/about.svg"
                style="object-fit: cover"
              />
              <div
                class="position-absolute top-0 start-0 bg-white rounded pe-3 pb-3"
              >
                <div
                  class="d-flex flex-column justify-content-center text-center bg-primary rounded h-100 p-3"
                >
                  <h1 class="text-white mb-0">{{ lang.about_badge_no }}</h1>
                  <h2 class="text-white">{{ lang.about_badge_1_word }}</h2>
                  <h5 class="text-white mb-0">{{ lang.about_badge_2_word }}</h5>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-6 wow fadeInUp" data-wow-delay="0.5s">
            <div class="h-100">
              <h1 class="display-6 mb-5">
                {{ lang.about_title }}
              </h1>
              <p class="fs-5 text-dark mb-4 fs-5">
                {{ lang.about_1_desc }}
              </p>
              <div class="row g-4 mb-4">
                <div class="col-sm-6">
                  <div class="d-flex align-items-center">
                    <img
                      class="flex-shrink-0 me-3 brownish-icon-svg"
                      src="@/assets/img/icon/icon-04-primary.png"
                      alt=""
                    />
                    <h5 class="mb-0">{{ lang.about_1_icon }}</h5>
                  </div>
                </div>
                <div class="col-sm-6">
                  <div class="d-flex align-items-center">
                    <img
                      class="flex-shrink-0 me-3 brownish-icon-svg"
                      src="@/assets/img/icon/icon-03-primary.png"
                      alt=""
                    />
                    <h5 class="mb-0">{{ lang.about_2_icon }}</h5>
                  </div>
                </div>
              </div>
              <p class="mb-4 fs-5">
                {{ lang.about_2_desc }}
              </p>
              <!-- <div class="border-top mt-4 pt-4">
                <div class="d-flex align-items-center">
                  <img
                    width="60"
                    height="60"
                    class="flex-shrink-0 blue-icon-svg me-3 "
                    src="@/assets/icons/square-phone-solid.svg"
                    alt=""
                  />
                  <h5 class="mb-0">{{ lang.phone_number }}</h5>
                </div>
              </div> -->
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'EnAbout',
    props: {
      lang: Object,
    }
}
</script>

<style>

</style>
