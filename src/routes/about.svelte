<style>
  figure {
    float: right;
    margin: -3em -7em 2em 2em;
    max-width: 400px;
  }

  figure img {
    border-radius: 8px;
  }

  @media (max-width: 1020px) {
    figure {
      float: none;
      margin: 0 auto 2em;
    }
  }
</style>

<svelte:head>
  <title>About</title>
</svelte:head>

<div class="container">
  <h2>About</h2>
  <figure>
    <img src='headshot.jpg' alt='A vintage typewriter.'>
  </figure>
 <p>
    Hi, I'm <strong>Ellis</strong>. I'm a software engineer and blockchain enthusiast from Colorado, USA.
    You can see some of my work on <a href="https://www.github.com/ellisbywater" target="_blank">GitHub</a>,
    or find more about what I am to in the crypto space with <a href="https://roguedefi.com" target="_blank">Rogue Defi</a>.
  </p>
</div>
