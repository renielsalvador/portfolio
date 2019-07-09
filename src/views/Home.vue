<template>
  <div>
    <header>
      <h1>
        Hi, I'm
        <span class="highlight">Reniel Salvador</span>
      </h1>
      <h3>I'm a full-stack web developer.</h3>
      <a href>View my work</a>
    </header>
    <nav>
      <ul>
        <li>Home</li>
        <li>About</li>
        <li>Projects</li>
        <li>Contact</li>
      </ul>
    </nav>
    <div class="content">
      <section class="about">
        <h2>About</h2>
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
      </section>
      <section class="projects">
        <h2>Projects</h2>
        <ul>
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
      <section class="contact">
        <div class="flags">
          <span class="flag"></span>
          <span class="flag"></span>
          <span class="flag"></span>
          <span class="flag"></span>
        </div>
        <div class="form-area">
          <h2>Contact</h2>
          <p class="sub-title"></p>
          <input type="text" />
          <input type="text" />
          <input type="text" />
          <textarea name cols="30" rows="10"></textarea>
          <button>SUBMIT</button>
        </div>
      </section>
    </div>
    <footer>
      <i class="dividier"></i>
      <div class="social">
        <span>
          <i class="fa fa-facebook"></i>
        </span>
        <span>
          <i class="fa fa-facebook"></i>
        </span>
        <span>
          <i class="fa fa-facebook"></i>
        </span>
      </div>
      <span>
        RENIEL SALVADOR
        <span class="copyright">
          <i class="fa fa-copyright"></i>2019
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
