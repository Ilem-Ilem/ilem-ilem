<template>
    <section id="skills" class="skills section">

        <!-- Section Title -->
        <div class="container section-title tw-mb-14" data-aos="fade-up">
            <h2 class="skill_title tw-font-[Castoro] tw-text-4xl tw-font-black tw-mb-14">Skills</h2>
            <p> Over the course of my journey as a web developer, I have acquired and honed a diverse set of skills that
                enable me to build robust, efficient, and visually appealing web applications. My expertise spans across
                both frontend and backend development, allowing me to create seamless user experiences and scalable
                solutions.</p>
        </div><!-- End Section Title -->

        <div class="container" data-aos="slide-in" data-aos-delay="100">

            <div class="row skills-content skills-animation">

                <div class="col-lg-6">

                    <div class="skill">
                        <span class="skill"><span>HTML</span> <i class="val">100%</i></span>
                      
                    </div><!-- End Skills Item -->

                    <div class="skill">
                        <span class="skill"><span>CSS / Tailwind</span> <i class="val">90%</i></span>
                      
                    </div><!-- End Skills Item -->

                    <div class="skill">
                        <span class="skill"><span>JavaScript / TypeScript</span> <i class="val">75%</i></span>
                       
                    </div><!-- End Skills Item -->
                    <div class="skill">
                        <span class="skill"><span>Alpine Js</span> <i class="val">75%</i></span>
                      
                    </div><!-- End Skills Item -->

                </div>

                <div class="col-lg-6">

                    <div class="skill">
                        <span class="skill"><span>Vue Js</span> <i class="val">65%</i></span>
                       
                    </div><!-- End Skills Item -->
                    <div class="skill">
                        <span class="skill"><span>PHP</span> <i class="val">80%</i></span>
                        
                    </div><!-- End Skills Item -->

                    <div class="skill">
                        <span class="skill"><span>Lavarel / Inertia</span> <i class="val">90%</i></span>
                        
                       
                    </div><!-- End Skills Item -->

                    <div class="skill">
                        <span class="skill"><span>Symfony</span> <i class="val">55%</i></span>
                       
                    </div><!-- End Skills Item -->

                </div>

            </div>

        </div>

    </section><!-- /Skills Section -->

</template>
<style scoped>
/*--------------------------------------------------------------
# Skills Section
--------------------------------------------------------------*/
.skill_title::after {
    content: '02';
    position: absolute;
    left: 0;
    top: 0;
    font-size: 90px;
    color: rgb(227, 192, 192);
    ;
    z-index: -1;
    margin-top: 10px;
    margin-bottom: 6rem !important;
}

.skill_title {
    margin-top: 30px;
    position: relative;
    margin-bottom: 5rem !important;
}

.skills .skill {
    height: 60px;
    display: block;
    background: none;
    border-radius: 0;
}

.skills .skill .skill {
    color: rgb(55, 3, 3);
    padding: 0;
    margin: 0 0 6px 0;
    text-transform: uppercase;
    display: block;
    font-weight: 600;
    font-family: poppin;
}

.skills .skill .skill .val {
    float: right;
    font-style: normal;
}

</style>