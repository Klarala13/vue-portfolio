<template>
  <div>
    <div class="container" id="projects">
      <h1>Projects</h1>
      <hr />
      <div class="row">
        <div class="col-lg 3 col-md-4 col-sm-12 col-xs-12">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Snake Game</h5>
              <p class="card-text">
                Let's go back to the 90's! Basic Snake Game with vanilla JS (no
                ES6)
              </p>
              <a
                href="https:/klarala13.github.io/Snake-Game/"
                target="_blank"
                class="btn btn-outline-dark"
                >The project</a
              >
            </div>
          </div>
        </div>
        <div class="col-lg 3 col-md-4 col-sm-12 col-xs-12">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">ToDo List</h5>
              <p class="card-text">
                React/Redux ToDo List. Implementing Local Storage.
              </p>
              <a
                href="https://klarala13.github.io/ToDo-List/"
                target="_blank"
                class="btn btn-outline-dark"
                >The project</a
              >
            </div>
          </div>
        </div>
        <div class="col-lg 3 col-md-4 col-sm-12 col-xs-12">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Weather API</h5>
              <p class="card-text">
                <b>Development mode only</b> Command Line Interface Weather App.
                Built with Axios & Dotenv.
              </p>
              <a
                href="https://github.com/Klarala13/WeatherServiceAPI"
                target="_blank"
                class="btn btn-outline-dark"
                >The project</a
              >
            </div>
          </div>
        </div>
      </div>

      <div class="row mt-3">
        <div class="col-lg 3 col-md-4 col-sm-12 col-xs-12">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Monster Game</h5>
              <p class="card-text">
                Simple Vue Game. Sometimes coding is just for fun.
              </p>
              <a
                href="https://klarala13.github.io/Monster-Game/"
                target="_blank"
                class="btn btn-outline-dark"
                >The project</a
              >
            </div>
          </div>
        </div>

        <div class="col-lg 3 col-md-4 col-sm-12 col-xs-12">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Dad Jokes</h5>
              <p class="card-text">
                Vue.js and nuxt SPA that gets silly jokes from API.
              </p>
              <a
                href="https://klarala13.github.io/DadJokesApi-nuxt/"
                target="_blank"
                class="btn btn-outline-dark"
                >The project</a
              >
            </div>
          </div>
        </div>

        <div class="col-lg 3 col-md-4 col-sm-12 col-xs-12">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Job Crawler</h5>
              <p class="card-text">
                <b>Development mode only</b> Crawl different web pages and sends
                email. Using Cron, Yargs and promises.
              </p>
              <a
                href="https://github.com/Klarala13/job-crawler"
                target="_blank"
                class="btn btn-outline-dark"
                >The project</a
              >
            </div>
          </div>
        </div>
      </div>

      <div class="row mt-3">
        <div class="col-lg 3 col-md-4 col-sm-12 col-xs-12">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Calcoolator</h5>
              <p class="card-text">Simple React calculator</p>
              <a
                href="https://klarala13.github.io/React-calculator/"
                target="_blank"
                class="btn btn-outline-dark"
                >The project</a
              >
            </div>
          </div>
        </div>
        <div class="col-lg 3 col-md-4 col-sm-12 col-xs-12">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Step Sequencer</h5>
              <p class="card-text">
                <b>DCI Hackathon 1st prize (joint project).</b> Step Sequencer
                using vanilla JS, HTML and Bootstrap.
              </p>
              <a
                target="_blank"
                class="btn btn-outline-dark"
                href="src/personalProjects/hackathon/extended-drum-kit-sounds/index.html"
                >The Project
              </a>
            </div>
          </div>
        </div>
        <div class="col-lg 3 col-md-4 col-sm-12 col-xs-12">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Mood Enhancer</h5>
              <p class="card-text">
                DCI class project where we won the teamwork award based on our
                use of Trello and the organnization and planning of the project.
              </p>
              <a
                target="_blank"
                class="btn btn-outline-dark"
                href="src/personalProjects/team-monday-morning/index.html"
                >The Project
              </a>
            </div>
          </div>
        </div>
      </div>

      <!--
        CONTACT LIST
        AJO QUOTES
        COLLECTIVITY
      -->

      <!--                 <div class="col-lg 3 col-md-3 col-sm-12 col-xs-12">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Contact List</h5>
              <p class="card-text">
                <b>Not yet Deployed</b> Has a small server faked with
                jason-server that allows for saving, updating and deleting
                contacts.
              </p>
              <a
                href="https://klarala13.github.io/contactList/"
                target="_blank"
                class="btn btn-outline-dark"
                >The project</a
              >
            </div>
          </div>
        </div> -->

      <!--    <div class="col-4">
            <div class="card">
              <div class="card-body">
                <h5 class="card-title">AjoQuotes</h5>
                <p class="card-text">
                  Developed in Vue.
                </p>
               <a href="#" class="btn btn-outline-dark">The Project</a> 
              </div>
            </div>
          </div> -->
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      paths: {
        avatar: "",
      },
    };
  },
};
</script>
