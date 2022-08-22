<template>
    <div class="container-xxl py-5" id="values">
      <div class="container">
        <div class="row g-5">
          <div class="col-lg-6 wow fadeInUp" data-wow-delay="0.1s">
            <h1 class="display-6 mb-5">{{ lang.values_title }}</h1>
            <p class="mb-4 fs-5">
              {{ lang.values_desc }}
            </p>
            <div class="row g-3">
              <div class="col-sm-6 wow fadeIn" data-wow-delay="0.1s">
                <div class="bg-light rounded h-100 p-3">
                  <div
                    class="bg-white d-flex flex-column justify-content-center text-center rounded h-100 py-4 px-3"
                  >
                    <img
                      class="align-self-center mb-3 brownish-icon-svg"
                      src="@/assets/img/icon/icon-06-primary.png"
                      alt=""
                    />
                    <h5 class="mb-0">{{ lang.values_1_icon }}</h5>
                  </div>
                </div>
              </div>
              <div class="col-sm-6 wow fadeIn" data-wow-delay="0.2s">
                <div class="bg-light rounded h-100 p-3">
                  <div
                    class="bg-white d-flex flex-column justify-content-center text-center rounded py-4 px-3"
                  >
                    <img
                      class="align-self-center mb-3 brownish-icon-svg"
                      src="@/assets/img/icon/icon-03-primary.png"
                      alt=""
                    />
                    <h5 class="mb-0">{{ lang.values_2_icon }}</h5>
                  </div>
                </div>
              </div>
              <div class="col-sm-6 wow fadeIn" data-wow-delay="0.3s">
                <div class="bg-light rounded h-100 p-3">
                  <div
                    class="bg-white d-flex flex-column justify-content-center text-center rounded py-4 px-3"
                  >
                    <img
                      class="align-self-center mb-3 brownish-icon-svg"
                      src="@/assets/img/icon/icon-04-primary.png"
                      alt=""
                    />
                    <h5 class="mb-0">{{ lang.values_3_icon }}</h5>
                  </div>
                </div>
              </div>
              <div class="col-sm-6 wow fadeIn" data-wow-delay="0.4s">
                <div class="bg-light rounded h-100 p-3">
                  <div
                    class="bg-white d-flex flex-column justify-content-center text-center rounded h-100 py-4 px-3"
                  >
                    <img
                      class="align-self-center mb-3 brownish-icon-svg"
                      src="@/assets/img/icon/icon-07-primary.png"
                      alt=""
                    />
                    <h5 class="mb-0">{{ lang.values_4_icon }}</h5>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-6 wow fadeInUp" data-wow-delay="0.5s">
            <div
              class="position-relative rounded overflow-hidden h-100"
              style="min-height: 400px"
            >
              <img
                class="position-absolute w-100 h-100"
                src="@/assets/icons/remote-ideation.svg"
                alt=""
                style="object-fit: cover"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'EnFeatures',
    props: {
      lang: Object,
    }
}
</script>
