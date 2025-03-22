<template>
    <section id="about" class="about section">

        <!-- Section Title -->
        <div class="container section-title" data-aos="fade-up">
            <div class="tw-relative tw-w-fit tw-h-fit tw-mb-8">
                <h1 class="tw-font-[Castoro] tw-text-4xl tw-font-black about_title tw-relative">About ME</h1>
            </div>
            <p>I am a self-taught web developer who started coding in <b>2019</b>. Over the years, I have developed a strong foundation in both backend and frontend technologies, including Laravel, HTML, CSS, JavaScript, TypeScript, and Vue.js. I am passionate about creating efficient, scalable, and user-friendly web applications while continuously learning new techniques and frameworks to stay ahead in this fast-evolving field.</p>
        </div><!-- End Section Title -->

        <div class="container" data-aos="fade-up" data-aos-delay="100">

            <div class="row gy-4 justify-content-center tw-mt-3">

                <div class="col-lg-4">
                    <img src="/img/IMG-20240422-WA0014.jpg" class="img-fluid" alt="">
                </div>
                <div class="col-lg-8 content">
                    <h2>Web Developer.</h2>
                    <p class="fst-italic py-3">
                       
                    </p>
                    <div class="row">
                        <div class="col-lg-6">
                            <ul>
                                <li><i class="bi bi-chevron-right tw-text-red-300"></i> <strong>Birthday:</strong> <span>10<sub>th</sub>
                                        January
                                        2002</span></li>
                                <li><i class="bi bi-chevron-right tw-text-red-300"></i> <strong>Phone:</strong> <span>+234 8168 950
                                        922</span></li>
                                <li><i class="bi bi-chevron-right tw-text-red-300"></i> <strong>City:</strong> <span>Calabar, CRS,
                                        Nigeria</span>
                                </li>
                                <li><i class="bi bi-chevron-right tw-text-red-300"></i> <strong>Freelance:</strong>
                                    <span>Available</span></li>
                            </ul>
                        </div>
                        <div class="col-lg-6">
                            <ul>
                                <li><i class="bi bi-chevron-right"></i> <strong>Age:</strong> <span>24</span></li>
                                <li><i class="bi bi-chevron-right"></i> <strong>Degree:</strong> <span>BSc</span></li>
                                <li><i class="bi bi-chevron-right"></i> <strong>Email:</strong>
                                    <span>Therealteckyguys@gmail.com</span>
                                </li>

                            </ul>
                        </div>
                    </div>
                    <p class="py-3">
                        Officiis eligendi itaque labore et dolorum mollitia officiis optio vero. Quisquam sunt adipisci
                        omnis et
                        ut. Nulla accusantium dolor incidunt officia tempore. Et eius omnis.
                        Cupiditate ut dicta maxime officiis quidem quia. Sed et consectetur qui quia repellendus itaque
                        neque.
                    </p>
                </div>
            </div>

        </div>

    </section><!-- /About Section -->
</template>
<style scoped>
.about_title::after {
    content: '01';
    position: absolute;
    left: 0;
    top: 0;
    font-size: 90px;
    color: rgb(227, 192, 192);
    z-index: -1;
    margin-top: 10px;
    margin-bottom: 5rem !important;

}

.about_title {
    margin-top: 30px;
    margin-bottom: 5rem !important;

}

.about .content h2 {
    font-weight: 700;
    font-size: 24px;
}

.about .content ul {
    list-style: none;
    padding: 0;
}

.about .content ul li {
    margin-bottom: 20px;
    display: flex;
    align-items: center;
}

.about .content ul strong {
    margin-right: 10px;
}

.about .content ul i {
    font-size: 16px;
    margin-right: 5px;
    color: var(--accent-color);
    line-height: 0;
}
</style>