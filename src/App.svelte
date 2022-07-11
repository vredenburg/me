<script lang="ts">
  import { Styles } from 'sveltestrap';
  import logo from './assets/me.jpeg'
</script>

<div class="container">
  <nav class="navbar navbar-expand-lg">
    <div class="container-md">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Me</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Development</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Photography</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Blog</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <main>
    <div class="container-fluid px-4 py-5 my-5 text-center w-50">
      <div class="row">
        <div class="col">
          <h1 class="text-primary">Hi, I'm Ian 👋</h1>
          <h4 class=" text-start">I'm a Software Engineer with a specialisation in Backend Development. Java is my language of choice. I design and develop complex backend systems.</h4>
        </div>
        <div class="col">
          <img src={logo} alt="Svelte Logo" class="rounded-pill border border-primary p-2"/>
        </div>
      </div>
    </div>
    
  </main>
</div>

<style>

  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }

  img {
    height: 12rem;
    width: 12rem;
  }

  h1 {
    font-size: 4rem;
    font-weight: 100;
    line-height: 1.1;
    margin: 2rem auto;
    max-width: 14rem;
  }

  p {
    max-width: 14rem;
    margin: 1rem auto;
    line-height: 1.35;
  }
</style>
