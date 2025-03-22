<template>
  <section id="resume" class="resume section">

    <!-- Section Title -->
    <div class="container section-title" data-aos="fade-up">
      <h2 class="resume_head_title tw-font-[Castoro] tw-text-4xl tw-font-black tw-mb-14">Resume</h2>
      <p>Magnam dolores commodi suscipit. Necessitatibus eius consequatur ex aliquid fuga eum quidem. Sit sint
        consectetur velit. Quisquam quos quisquam cupiditate. Et nemo qui impedit suscipit alias ea. Quia fugiat
        sit in iste officiis commodi quidem hic quas.</p>
    </div><!-- End Section Title -->

    <div class="container tw-mt-5">

      <div class="row">

        <div class="col-lg-6" data-aos="fade-up" data-aos-delay="100">
          <h3 class="resume-title">Sumary</h3>

          <div class="resume-item pb-0">
            <h4>Ilem I. Ogban</h4>
            <p>Self-motivated and detail-oriented web developer with over 5 years of experience specializing in backend
              and frontend development. Proficient in Laravel, HTML, CSS, JavaScript, TypeScript, and Vue.js, with a
              strong understanding of modern web technologies. Passionate about building efficient and scalable web
              applications.</p>
            <ul>
              <li>Portland par 127,Orlando, FL</li>
              <li>(123) 456-7891</li>
              <li>alice.barkley@example.com</li>
            </ul>
          </div><!-- Edn Resume Item -->

          <h3 class="resume-title">Education</h3>
          <div class="resume-item">
            (Self-taught since 2019)
          </div>
        </div>

        <div class="col-lg-6" data-aos="fade-up" data-aos-delay="200">
          <h3 class="resume-title">Professional Experience</h3>
          <div class="resume-item">
            <h4>Freelance Web Developer</h4>
            <h5>2019 - Present</h5>
            <p>Experion, New York, NY </p>
            <ul>
              <li>Designed and developed full-stack web applications using Laravel and Vue.js.</li>

              <li>Created and maintained responsive user interfaces with HTML, CSS, and JavaScript.</li>

              <li>Integrated APIs and databases to enhance application functionality.</li>

              <li>Provided technical support and troubleshooting for web applications.</li>

              <li>Kept up with industry trends and improved coding best practices.</li>

            </ul>
          </div><!-- Edn Resume Item -->

          <div class="resume-item">
            <h4>Graphic design specialist</h4>
            <h5>2017 - 2018</h5>
            <p>Stepping Stone Advertising, New York, NY</p>
            <ul>
              <li>Developed numerous marketing programs (logos, brochures,infographics, presentations, and
                advertisements).</li>
              <li>Managed up to 5 projects or tasks at a given time while under pressure</li>
              <li>Recommended and consulted with clients on the most appropriate graphic design</li>
              <li>Created 4+ design presentations and proposals a month for clients and account managers
              </li>
            </ul>
          </div><!-- Edn Resume Item -->

        </div>

      </div>

    </div>

  </section><!-- /Resume Section -->

</template>
<style scoped>
/*--------------------------------------------------------------
# Resume Section
--------------------------------------------------------------*/
.resume_head_title::after {
  content: '03';
  position: absolute;
  left: 0;
  top: 0;
  font-size: 90px;
  color: rgb(227, 192, 192);
  z-index: -1;
  margin-top: 10px;
  margin-bottom: 6rem !important;
}

.resume_head_title {
  margin-top: 30px;
  position: relative;
  margin-bottom: 5rem !important;
}

.resume-title {
  font-size: 20px;
  font-family: poppins, 'Times New Roman', Times, serif;
  color: rgb(141, 141, 141);
}

.resume .resume-item {
  padding: 0 0 20px 20px;
  margin-top: -2px;
  border-left: 2px solid rgb(112, 2, 2);
  position: relative;
}

.resume .resume-item h4 {
  line-height: 18px;
  font-size: 18px;
  font-weight: 600;
  text-transform: uppercase;
  color: color-mix(in srgb, rgb(112, 2, 2), transparent 20%);
  margin-bottom: 10px;
}

.resume .resume-item h5 {
  font-size: 16px;
  padding: 5px 15px;
  display: inline-block;
  font-weight: 600;
  margin-bottom: 10px;
}

.resume .resume-item ul {
  padding-left: 20px;
}

.resume .resume-item ul li {
  padding-bottom: 10px;
}

.resume .resume-item:last-child {
  padding-bottom: 0;
}

.resume .resume-item::before {
  content: "";
  position: absolute;
  width: 16px;
  height: 16px;
  border-radius: 50px;
  left: -9px;
  top: 0;
  background: rgb(112, 2, 2);
  border: 2px solid rgb(112, 2, 2);
}
</style>