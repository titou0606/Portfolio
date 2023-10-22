<template>
  <div class="bg-green-50 page-section pt-5 -mb-5">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 py-3 wow zoomIn">
          <div class="img-place text-center hidden lg:flex">
            <lottie-player
              src="https://assets2.lottiefiles.com/packages/lf20_qhrndegx.json"
              background="transparent"
              speed="1"
              style="max-width: 500px; max-height: 500px"
              autoplay></lottie-player>
          </div>
        </div>

        <div class="col-lg-6 p-4">
          <h2 class="title-section text-2xl">
            All About
            <span class="marked">Myself</span>
          </h2>
          <div class="divider"></div>

          <div>
            <p>
              I am a Creative Technology student at the De Vinci Innovation Center. 
              Members of the "Resilient Futures" group are dedicated to developing 
              sustainable and resilient technologies that can address the challenges
               of climate change. I am passionate about biomimicry, which involves 
               taking inspiration from nature to create sustainable solutions.
                I am intensely interested in sustainable and low-tech technologies,
                 fabrication processes, and programing.
            </p>
          </div>

          <div>
            <p>
              I have had some experience in business development through my Master 1 
              internship in a French start-up for 4 months. I have spent 4 months in 
              Canada and in Latvia for exchanges programs. I play the piano for 14 years
              and love playing badminton in competition.  
            </p>
          </div>

          <div>
            <p class="hidden lg:flex">
              And I'm interested in all the innovative and research & development
              spectrum, and working on ambitious projects with positive people.
            </p>
          </div>

          <div class="img-place mb-3"></div>
          <a href="#" class="btn btn-primary">More Details</a>
          <a href="#" class="btn btn-outline border ml-2">Success Stories</a>
        </div>
      </div>
    </div>
    <!-- .container -->
  </div>
  <!-- .page-section -->

  <div class="bg-green-50 page-section">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 p-4 -mt-9 lg:mt-0">
          <h2 class="title-section text-2xl">
            My
            <span class="marked">Skills & Experiences</span>
          </h2>
          <div class="divider"></div>
          <p class="mb-4">
            I have had some experience in business development through my Master 1 
            internship in a French start-up for 4 months. 
            I am a last year student in Creative Technology at ESILV (at la Defense).
            I'm doing a double diploma at EMLV in Management. 
            In addition, my school provides me with several formations of soft skills
            to introduce us to new ways of co-working, through communication exercices
            and hackathon.
            
          </p>
          <p class="mb-4">
            I have had some experience in business development through my Master 1 
            internship in a French start-up for 4 months. I was in charge of gathering 
            customers data, of CRM Management. I also took charge of automations between
            it and other tools thanks to a no-code plateform for more efficiency.
          </p>

          <p class="mb-5 hidden lg:flex">
            
          </p>

          <!-- <router-link to="/blog" class="btn btn-primary">My Blogs</router-link> -->
          <router-link to="/projects" class="btn btn-outline ml-2">
            My Projects
          </router-link>
        </div>
        <div class="col-lg-6 py-3 wow zoomIn">
          <div class="img-place text-center">
            <lottie-player
              src="https://assets2.lottiefiles.com/packages/lf20_u4jjb9bd.json"
              background="transparent"
              speed="0.5"
              style="max-width: 550px; max-height: 550px"
              loop
              autoplay></lottie-player>
          </div>
        </div>
      </div>
    </div>
    <!-- .container -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      scrollPosition: 0,
    };
  },

  methods: {
    handleScroll(e) {
      this.scrollPosition = e.target.scrollTop;

      if (this.scrollPosition > 100) {
        console.log("UP");
      } else {
        console.log("DOWN");
      }
    },
  },
};
</script>

<style></style>
