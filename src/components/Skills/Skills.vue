<template>
  <div>
    <div class="container mt-5" id="skills">
      <div class="row">
        <div class="col-12">
          <h1>Skills</h1>
          <hr />
          <div class="experience-nav row m-3">
            <div>
              <b-tabs content-class="mt-3">
                <b-tab title="Just me" active>
                  <div class="col-12">
                    <img
                      src="/images/profile.jpg"
                      class="rounded float-left about-img mr-3"
                      alt="Me, developing"
                    />
                    <div>
                      <p class="mt-2">
                        I have been falling in love with both the front and the
                        backend for the past two years now. I am currently
                        working at
                        <a href="https://www.wheelhub.es/" target="blank"
                          >Wheelhub Apps
                        </a>
                        am honored happy to be a part of their team. Every day I
                        learn something new and I am lucky enough to be
                        surrounded by amazing collegues.
                        <br />
                        I also try to help out at the
                        <a href="https://codebar.io/" target="blank">
                          Codebar
                        </a>
                        workshops for the last year or so. I participate as a
                        coach at their workshops and am now part of a team
                        trying to develop a pairing tool we can use in the
                        workshops. But that's not all I've done so, what do web
                        developing, waitressing, journalism and the fashion
                        industry have in common? Me. I am not just a developer.
                        I am many more things. Some of them are good, some bad,
                        some great… if you want to know more you can check out
                        my different projects, certificates, etc or just drop me
                        a line on my contact form!
                      </p>
                    </div>
                  </div></b-tab
                >
                <b-tab title="Wheelhub"><p>Some wheelhub info</p></b-tab>
                <b-tab title="Codebar">
                  <div class="row">
                    Codebar is a project born out of the necessity to give
                    minorities a chance at equal opportunities. The idea is to
                    bring students and coaches together and the coaches help the
                    students with a project of their choice or in one of the
                    Codebar
                    <a href="http://tutorials.codebar.io/" target="_blank"
                      >tutorials </a
                    >that are available on thir site. It recently achieved the
                    status of
                    <a
                      href="https://medium.com/the-codelog/codebar-the-charity-85f934698f7c"
                      target="_blank"
                      >charity</a
                    >, and I am proud to say I have coached at some of their
                    events and am helping out in the development of a pairing
                    tool.
                  </div>
                  <div class="row">
                    <b-embed
                      type="video"
                      src="https://youtu.be/81FrIQafDmU"
                      allowfullscreen
                      controls
                    >
                    </b-embed>
                  </div>
                </b-tab>
              </b-tabs>
            </div>
          </div>
        </div>
      </div>
    </div>
    <stack></stack>
  </div>
</template>

<script>
import Stack from "./Stack.vue";

export default {
  components: {
    stack: Stack,
  },
};
</script>
