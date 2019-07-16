<template>
  <div>
    <section class="hero is-fullheight has-text-centered">
      <div class="hero-body">
        <div class="container">
          <div class="columns">
            <div class="column is-10 is-offset-1">
              <h1 class="title">
                Hi, I'm
                <span class="highlight">Reniel Salvador</span>.
              </h1>
              <h2 class="subtitle">I'm a full-stack web developer.</h2>
              <a href class="is-pulled-right">
                View my work
                <i class="fas fa-long-arrow-alt-right"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="container">
        <div class="navbar-brand">
          <a
            role="button"
            class="navbar-burger burger"
            aria-label="menu"
            aria-expanded="false"
            data-target="navbarBasicExample"
          >
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>

        <div id="navbarBasicExample" class="navbar-menu">
          <div class="navbar-start">
            <a class="navbar-item">Home</a>
            <a class="navbar-item">About</a>
            <a class="navbar-item">Portfolio</a>
            <a class="navbar-item">Contact</a>
          </div>
        </div>
      </div>
    </nav>
    <div class="content container">
      <section class="about">
        <h2 class="title">About</h2>
        <ul class="offers">
          <li>
            <article>
              <h4>Dynamic</h4>
              <hr />
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </article>
          </li>
          <li>
            <article>
              <h4>Dynamic</h4>
              <hr />
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </article>
          </li>
          <li>
            <article>
              <h4>Dynamic</h4>
              <hr />
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </article>
          </li>
        </ul>

        <article class="about-me">
          <div class="about-me-start">
            <span class="avatar">
              <img src="../assets/profile.jpg" alt="profile.jpg" />
            </span>
            <div class="information">
              <h5 class="title">Who am I?</h5>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit,
                sed do eiusmod tempor incididunt ut labore et
                dolore magna aliqua. Ut enim ad minim veniam,
                quis nostrud
              </p>
            </div>
          </div>
          <div class="skills-percentage">
            <ul class="skills">
              <li>
                <h6>First skill 1</h6>
                <div class="bar">
                  <span class="progress-bar">
                    <span class="percent">80%</span>
                  </span>
                  <input type="range" />
                </div>
              </li>
              <li>
                <h6>First skill 1</h6>
                <div class="bar">
                  <span class="progress-bar">
                    <span class="percent">80%</span>
                  </span>
                  <input type="range" />
                </div>
              </li>
              <li>
                <h6>First skill 1</h6>
                <div class="bar">
                  <span class="progress-bar">
                    <span class="percent">80%</span>
                  </span>
                  <input type="range" />
                </div>
              </li>
            </ul>
          </div>
        </article>
      </section>
      <section class="projects">
        <h2 class="title">Projects</h2>
        <ul class="projects-list">
          <li>
            <div class="img-container">
              <img src="../assets/logo.png" alt />
            </div>
            <div class="cover">
              <h3>Project 1</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </div>
          </li>
          <li>
            <div class="img-container">
              <img src="../assets/logo.png" alt />
            </div>
            <div class="cover">
              <h3>Project 1</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </div>
          </li>
          <li>
            <div class="img-container">
              <img src="../assets/logo.png" alt />
            </div>
            <div class="cover">
              <h3>Project 1</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </div>
          </li>
        </ul>
      </section>
    </div>

    <section class="contact">
      <div class="flags">
        <span class="flag"></span>
        <span class="flag"></span>
        <span class="flag"></span>
        <span class="flag"></span>
      </div>
      <div class="form-area">
        <h2 class="title">Contact</h2>
        <p class="sub-title has-text-centered">Have questions or want to work together?</p>
        <div class="field">
          <div class="control">
            <input class="input is-medium" type="text" placeholder="Info input">
          </div>
        </div>
        <div class="field">
          <div class="control">
            <input class="input is-medium" type="text" placeholder="Info input">
          </div>
        </div>
        <div class="field">
          <div class="control">
            <textarea class="textarea is-medium" name cols="10" rows="5"></textarea>
          </div>
        </div>
        <button class="button is-aligned-right is-medium">SUBMIT</button>
      </div>
    </section>
    <footer>
      <span class="divider">
        <i class="fas fa-angle-double-up fa-4x"></i>
      </span>
      <div class="socials ">
        <span class="icon is-large">
          <i class="fab fa-facebook-f fa-2x"></i>
        </span>
        <span class="icon is-large">
          <i class="fab fa-instagram fa-2x"></i>
        </span>
        <span class="icon is-large">
          <i class="fab fa-linkedin-in fa-2x"></i>
        </span>
      </div>
      <span class="author">
        RENIEL SALVADOR
        <span class="copyright">
          <i class="far fa-copyright"></i> 2019
        </span>
      </span>
    </footer>
  </div>
</template>

<script>
export default {
  name: "home",
  components: {}
};
</script>
