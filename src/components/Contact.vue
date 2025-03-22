<template>
  <!-- Contact Section -->
  <section id="contact" class="contact section tw-mb-12">

    <!-- Section Title -->
    <div class="container section-title" data-aos="fade-up">
      <h2 class=" contact_title tw-relative tw-font-[Castoro] tw-text-4xl tw-font-black tw-mb-14">Contact</h2>
      <p>Necessitatibus eius consequatur ex aliquid fuga eum quidem sint consectetur velit</p>
    </div><!-- End Section Title -->

    <div class="container" data-aos="fade" data-aos-delay="100">

      <div class=" gy-4">

        <div class="md:tw-flex md:tw-justify-between">
          <div class="info-item tw-m-3" data-aos="fade-up" data-aos-delay="200">
            <i class="bi bi-geo-alt flex-shrink-0"></i>
            <div>
              <h3>Address</h3>
              <p>Mount Zion, Calbar, Cross River State Nigeria</p>
            </div>
          </div><!-- End Info Item -->

          <div class="info-item tw-m-3" data-aos="fade-up" data-aos-delay="300">
            <i class="bi bi-telephone flex-shrink-0"></i>
            <div>
              <h3>Call Me</h3>
              <a href="tel:+234816895092">+234 8168 950 92</a>
            </div>
          </div><!-- End Info Item -->

          <div class="info-item  tw-m-3" data-aos="fade-up" data-aos-delay="400">
            <i class="bi bi-envelope flex-shrink-0"></i>
            <div>
              <h3>Email Us</h3>
              <a href="mailto:therealteckyguys@gmail.com">therealteckyguys@gmail.com</a>
            </div>
          </div><!-- End Info Item -->

        </div>
        <div class="">
            <a href="https://wa.me/2348168950922?text=Hello%2C%20I%20just%20clicked%20this%20link%20from%20your%20profile%20page%20and%20wanted%20to%20reach%20out." class="d-flex tw-justify-center tw-mt-8 tw-w-full tw-rounded tw-bg-green-800 tw-text-whiite tw-font-bold tw-text-white tw-p-4 hover:tw-bg-green-500 float-right tw-px-4 tw-block"  data-aos="fade-up">Message Me On WhatsApp <i class="bi bi-whatsapp tw-ml-6"></i></a>

        </div>
      </div>

    </div>

  </section><!-- /Contact Section -->

</template>

<style scoped>
/*--------------------------------------------------------------
# Contact Section
--------------------------------------------------------------*/
.contact_title::after {
  content: '04';
  position: absolute;
  left: 0;
  top: 0;
  font-size: 90px;
  color: rgb(227, 192, 192);
  z-index: -1;
  margin-top: 10px;
  margin-bottom: 6rem !important;
}


.contact .info-item i {
  color: rgb(227, 118, 118);
  background: color-mix(in srgb, rgb(233, 0, 0), transparent 92%);
  font-size: 20px;
  width: 44px;
  height: 44px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50px;
  transition: all 0.3s ease-in-out;
  margin-right: 15px;
}
</style>
