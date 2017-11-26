<template>
  <section class="container">
    <div class="grid-container">
      <div class="grid-wrapper">
      </div>
      <header class="masthead">
        <div class="masthead-inner">
          <header class="site-title">
            <h1>Eliud C. Delgado</h1>
          </header>
          <nav class="main-nav">
            <ul class="hor-menu">
              <li>
                <a href="/about">About</a>
              </li>
              <li>
                <a href="#features">Servicios</a>
              </li>
              <li>
                <a href="#blog">Blog</a>
              </li>
              <li>
                <a href="#footer">Contacto</a>
              </li>
            </ul>
          </nav>
        </div>
      </header>
      <section class="hero">
        <div class="hero-inner">
          <h2>Acá va un título súper cabrón</h2>
          <p>Y luego de eso un subtítulo elocuente</p>
        </div>
      </section>
      <section class="features" id="features">
        <div class="features-inner">
          <article class="features-group">
            <div class="features-image">
              <img src="https://unsplash.it/300?image=930">
            </div>
            <div class="features-text">
              <h3>Aquí va otro título</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea iure quia autem repudiandae eligendi libero.</p>
            </div>
          </article>
          <article class="features-group">
            <div class="features-image">
              <img src="https://unsplash.it/300?image=970">
            </div>
            <div class="features-text">
              <h3>Aquí va otro título</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea iure quia autem repudiandae eligendi libero.</p>
            </div>
          </article>
          <article class="features-group">
            <div class="features-image">
              <img src="https://unsplash.it/300?image=780">
            </div>
            <div class="features-text">
              <h3>Aquí va otro título</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea iure quia autem repudiandae eligendi libero.</p>
            </div>
          </article>
        </div>
      </section>
      <section class="callout">
        <div class="callout-inner">
          <h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt, quas.</h3>
        </div>
      </section>
      <section class="blog" id="blog">
        <div class="blog-inner">
          <div class="blog-grid">
            <div class="blog-image">
              <img src="https://unsplash.it/300?image=39">
            </div>
            <div class="blog-text">
              <p class="blog-summary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit commodi earum nihil repellat maiores impedit
                dolore temporibus in. Autem, iusto?</p>
              <a class="button" href="#">Read More</a>
            </div>
            <div class="blog-image">
              <img src="https://unsplash.it/300?image=113">
            </div>
            <div class="blog-text">
              <p class="blog-summary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit commodi earum nihil repellat maiores impedit
                dolore temporibus in. Autem, iusto?</p>
              <a class="button" href="#">Read More</a>
            </div>
            <div class="blog-image">
              <img src="https://unsplash.it/300?image=56">
            </div>
            <div class="blog-text">
              <p class="blog-summary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit commodi earum nihil repellat maiores impedit
                dolore temporibus in. Autem, iusto?</p>
              <a class="button" href="#">Read More</a>
            </div>
          </div>
        </div>
        <div class="blog-cta">
          <a class="button ghost-button" href="#">More Stories</a>
        </div>
      </section>
      <section class="footer" id="footer">
        <div class="footer-inner">
          <div class="footer-grid">
            <div class="footer-group">
              <div class="footer-heading">
                <h4>Enseñanza</h4>
              </div>
              <div class="footer-links">
                <ul>
                  <li>
                    <a href="#">Link 1</a>
                  </li>
                  <li>
                    <a href="#">Link 2</a>
                  </li>
                  <li>
                    <a href="#">Link 3</a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="footer-group">
              <div class="footer-heading">
                <h4>Traducción</h4>
              </div>
              <div class="footer-links">
                <ul>
                  <li>
                    <a href="#">Link 1</a>
                  </li>
                  <li>
                    <a href="#">Link 2</a>
                  </li>
                  <li>
                    <a href="#">Link 3</a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="footer-group">
              <div class="footer-heading">
                <h4>Redacción</h4>
              </div>
              <div class="footer-links">
                <ul>
                  <li>
                    <a href="#">Link 1</a>
                  </li>
                  <li>
                    <a href="#">Link 2</a>
                  </li>
                  <li>
                    <a href="#">Link 3</a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="footer-group">
              <div class="footer-heading">
                <h4>Consultoría</h4>
              </div>
              <div class="footer-links">
                <ul>
                  <li>
                    <a href="#">Link 1</a>
                  </li>
                  <li>
                    <a href="#">Link 2</a>
                  </li>
                  <li>
                    <a href="#">Link 3</a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="footer-group">
              <div class="footer-heading">
                <h4>Sígueme</h4>
              </div>
              <div class="footer-links">
                <ul>
                  <li>
                    <a href="#">Link 1</a>
                  </li>
                  <li>
                    <a href="#">Link 2</a>
                  </li>
                  <li>
                    <a href="#">Link 3</a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
  </section>
</template>

<script>
</script>

<style>
.button,
.ghost-button {
  transition: background-color .2s ease-in-out, color .2s ease-in-out;
}

.blog-image img,
.features-image img {
  width: 100%;
}

.blog-text,
.callout-inner,
.features-text,
.hero-inner,
.masthead-inner {
  text-align: center;
}

.blog-grid,
.footer-grid,
.grid-wrapper {
  grid-template-rows: auto;
}

html {
  box-sizing: border-box;
}

*,
::after,
::before {
  box-sizing: inherit;
}

body {
  background-color: #fcfcff;
  color: #383838;
  font-family: Source Sans Pro, sans-serif;
  font-size: 16px;
  line-height: 1.5;
  margin: 0
}

a,
h1,
h2,
h3,
h4 {
  color: #fccd4e
}
  .grid-container {
  display: grid
}

.grid-wrapper {
  grid-template-columns: repeat(12, 100px);
  grid-gap: 2rem
}

.button {
  padding: .5rem 1rem;
  background: #fccd4e;
  color: #383838;
  text-decoration: none;
  font-size: 90%;
  display: inline-block;
  border-radius: 3px
}

.callout,
.hero,
.hor-menu {
  display: flex
}

.button:hover {
  background: #383838;
  color: #fccd4e
}

.ghost-button {
  padding: 1rem;
  background: 0 0;
  border: 3px solid #383838;
  color: #383838;
  font-variant: small-caps;
  font-weight: 600
}

.ghost-button:hover {
  background: #383838;
  color: #fcfcff
}

.masthead {
  background: #fccd4e;
  color: #fcfcff;
  min-height: 10vh
}

.hor-menu {
  list-style: none;
  margin: 0;
  justify-content: center;
  padding: 1rem 0
}

.hor-menu li {
  margin-left: 1rem
}

.hor-menu li a {
  color: #383838;
  font-weight: 300;
  font-size: 1rem;
  text-decoration: none
}

.hor-menu li a:hover {
  color: #fcfcff;
  text-decoration: underline
}

.site-title h1 {
  margin: 0;
  font-weight: 400;
  color: #383838
}

.hero {
  background: linear-gradient(rgba(0, 0, 0, .3), rgba(0, 0, 0, .3), rgba(0, 0, 0, .1), rgba(0, 0, 0, .7)), url(https://picsum.photos/2000?image=902);
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  min-height: 90vh;
  align-items: flex-end;
  justify-content: center
}

.hero-inner {
  max-width: 90%;
  padding-bottom: 10vh;
  color: #fcfcff;
  line-height: 1.2
}

.hero-inner h2 {
  color: #fcfcff;
  font-size: 2.5rem;
  font-weight: 600
}

.hero-inner p {
  font-size: 1.3rem;
  font-weight: 300
}

.features,
.features-inner {
  padding: 1rem
}

.features-group {
  padding-bottom: 1rem
}

.features-text p {
  margin-top: 0;
  width: 100%
}

.callout {
  align-items: center;
  justify-content: center;
  background: linear-gradient(rgba(56, 56, 56, .5), rgba(56, 56, 56, .5)), url(https://unsplash.it/1500?image=1041);
  background-position: center center;
  background-size: cover;
  background-repeat: no-repeat
}

.callout-inner h3 {
  color: #fcfcff;
  font-size: 2rem;
  font-weight: 600;
  padding: 1.5rem
}

.blog {
  padding: 2rem 0
}

.blog-inner {
  max-width: 800px;
  margin: auto;
  padding: 0 1rem
}

.blog-grid {
  display: grid;
  grid-template-columns: 1fr;
  grid-row-gap: 1rem
}

.blog-text {
  margin: 0
}

.blog-text p {
  text-align: left;
  width: 90%;
  margin: 0 auto;
  padding-bottom: 2rem
}

.blog-text a {
  margin-bottom: 2rem
}

.blog-cta {
  margin: 1.5rem 0 0;
  text-align: center
}

.blog-cta a {
  font-size: 1rem;
  font-weight: 400
}

.footer {
  background: #383838;
  color: #fcfcff;
  padding: 1.5rem;
  display: flexbox;
  justify-items: center;
  align-items: center
}

.footer-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 1rem;
  justify-items: center;
  text-align: center;
  width: 100%;
  max-width: 1000px;
  margin: 0 auto
}

.footer-group {
  max-width: 5rem
}

.footer-heading h4 {
  font-weight: 300;
  font-size: 1.5rem;
}

.footer-links ul {
  list-style: none;
  padding: 0;
}

.footer-links ul li {
  padding: .5rem 0;
  text-align: center;
}

.footer-links ul a {
  font-weight: 100;
  color: #fccd4e;
  transition: color .2s ease-in-out;
}

.footer-links ul a:hover {
  color: rgba(252, 205, 78, .7)
}

@media (min-width:600px) {
  .blog-text p,
  .features-text {
    text-align: left;
  }
  .masthead {
    padding: 1vh 4vh
  }
  .masthead-inner {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
  }
  .hor-menu {
    padding: 0
  }
  .hor-menu li a {
    font-size: 1.25rem;
  }
  .hero-inner {
    max-width: 75%;
  }
  .features {
    padding: 4rem;
  }
  .features-inner {
    display: flex;
    max-width: 800px;
    margin: auto;
  }
  .blog-grid,
  .footer-grid {
    display: grid;
    grid-template-rows: auto;
  }
  .features-group {
    flex: 0 1 30vw;
    padding-bottom: 0;
  }
  .features-group:nth-child(2) {
    margin: 0 2rem;
  }
  .features-image img {
    width: 100%;
  }
  .callout-inner h3 {
    font-size: 2.5rem;
    padding: 2rem;
  }
  .blog {
    padding: 5rem 0;
  }
  .blog-grid {
    grid-template-columns: 300px 1fr;
    grid-column-gap: 2rem;
    grid-row-gap: 2rem;
  }
  .blog-text p {
    width: 100%;
    margin: 0 auto;
    padding-bottom: 2rem;
  }
  .blog-text a {
    margin-bottom: 2rem;
  }
  .blog-cta {
    margin: 3rem 0 0;
  }
  .blog-cta a {
    font-size: 1.15rem;
  }
  .footer-grid {
    grid-template-columns: repeat(5, 1fr);
    grid-gap: 1rem;
    justify-items: center;
    width: 100%;
    max-width: 1000px;
    margin: auto;
  }
}
</style>
