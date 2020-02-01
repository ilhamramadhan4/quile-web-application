<template>
  <div>
    <div class="container">
      <nav class="navbar" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
          <a class="navbar-item" href="https://bulma.io">
            <img src="https://bulma.io/images/bulma-logo.png" width="112" height="28">
          </a>

          <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
            <span aria-hidden="true" />
            <span aria-hidden="true" />
            <span aria-hidden="true" />
          </a>
        </div>

        <div id="navbarBasicExample" class="navbar-end">
          <div class="navbar-start">
            <a class="navbar-item">
              Courses
            </a>

            <a class="navbar-item">
              About
            </a>

            <a class="navbar-item">
              Contact
            </a>

            <div class="navbar-item has-dropdown is-hoverable">
              <a class="navbar-link">
                Contact
              </a>

              <div class="navbar-dropdown">
                <a class="navbar-item">
                  About
                </a>
                <a class="navbar-item">
                  Jobs
                </a>
                <a class="navbar-item">
                  Contact
                </a>
                <hr class="navbar-divider">
                <a class="navbar-item">
                  Report an issue
                </a>
              </div>
            </div>
          </div>

          <div class="navbar-end">
            <div class="navbar-item">
              <div class="buttons">
                <a class="button is-primary is-rounded">
                  <strong>Sign In</strong>
                </a>
              </div>
            </div>
          </div>
        </div>
      </nav>

      <body>
        <section class="section">
          <div class="columns is-vcentered">
            <div class="column">
              <div class="container">
                <h1 class="title">
                  Our tagline goes here!!!
                </h1>
                <h2 class="subtitle">
                  Let's get started
                  <div class="buttons pad">
                    <a class="button is-outlined is-primary is-rounded">
                      <strong>Sign Up</strong>
                    </a>
                  </div>
                </h2>
              </div>
            </div>
            <div class="column vertical-center">
              <div class="container">
                <figure class="image is-600x600">
                  <img src="https://static-2.gumroad.com/res/gumroad/1211634803146/asset_previews/e5dad5e3f5b980d8b42e09f6d8adcd4b/retina/drawkit-server-woman-colour-thumbnail.png">
                </figure>
              </div>
            </div>
          </div>
        </section>

        <section class="section">
          <div class="columns">
            <div class="column">
              <div class="box">
                <article class="media">
                  <div class="media-content">
                    <div class="content">
                      <p>
                        <strong>Innovative courses with lots variety of subject</strong>
                        <br>
                        "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
                      </p>
                    </div>
                  </div>
                </article>
              </div>
            </div>
            <div class="column">
              <div class="box">
                <article class="media">
                  <div class="media-content">
                    <div class="content">
                      <p>
                        <strong>Innovative courses with lots variety of subject</strong>
                        <br>
                        We believe that we can provide any student with the necessary knowledge to overcome therirr curiousity.
                        <br>
                        We believe that we can provide any student with the necessary knowledge to overcome therirr curiousity.
                      </p>
                    </div>
                  </div>
                </article>
              </div>
            </div>
          </div>
        </section>
      </body>

      <footer class="footer">
        <div class="content has-text-centered">
          <p>
            <strong>Bulma</strong> by <a href="https://jgthms.com">Jeremy Thomas</a>. The source code is licensed
            <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The website content
            is licensed <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY NC SA 4.0</a>.
          </p>
        </div>
      </footer>

    </div>
  </div>
</template>

<script>
export default {
  components: {
  }
}
</script>

<style>
.pad {
  padding-top: .5em
}
</style>
