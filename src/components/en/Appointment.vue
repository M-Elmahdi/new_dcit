<template>
    <div
      class="container-fluid appointment mt-5 py-1 wow fadeIn"
      data-wow-delay="0.1s"
      id="contactus"
    >
      <div class="container pt-5 pb-1">
        <div class="row g-5">
          <div class="col-lg-6 wow fadeIn" data-wow-delay="0.3s">
          <div class="mt-3">
            <h1 class="display-6 text-white mb-5">
              {{ lang.geo_title }}
            </h1>
            <p class="text-white mb-5 fs-5">
              {{ lang.geo_desc }}
            </p>
            <div class="bg-primary border border-white rounded border-5 rounded p-1">
              <div class="d-flex align-items-center rounded p-2">
                <img
                  width="50"
                  height="50"
                  class="flex-shrink-0 white-icon-svg me-3"
                  src="@/assets/icons/phone-square-alt-solid.svg"
                  alt=""
                />
                <h5 class="text-white mb-0">{{ lang.phone_number }}</h5>
              </div>

              <div class="d-flex align-items-center rounded p-2">
                <img
                  width="50"
                  height="50"
                  class="flex-shrink-0 white-icon-svg me-3"
                  src="@/assets/icons/envelope-regular.svg"
                  alt=""
                />
                <h5 class="text-white mb-0">{{ lang.company_email }}</h5>
              </div>
            </div>
          </div>
            
          </div>
          <div class="col-lg-6 mt-0 wow fadeIn" data-wow-delay="0.5s">
            <div class="row rounded p-5">
              <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d211.2909131523757!2d20.106105889390577!3d32.07858931669537!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x13831d9f40abd28f%3A0x188f1354a329f18e!2zRENJVC3YtNix2YPYqSDYp9mE2LbZhdin2YYg2YTYqtmC2YbZitipINin2YTZhdi52YTZiNmF2KfYqg!5e0!3m2!1sen!2sly!4v1660042733994!5m2!1sen!2sly" width="600" height="450" style="border:0; border-radius: 10px;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'EnAppointment',
    props: {
      lang: Object,
    }
}
</script>
