<section>
  <div class="skins">
    <div class="container">
      <div class="layout">
        <div class="hero-content bg-gradient-blue white">
          <h1>Lorem ipsum dolor sit.</h1>
          <p class="white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente nulla soluta nesciunt tenetur. Autem, nobis quos?</p>
          <a class="button bg-gradient-pink white" href="/portfolio">View Portfolio</a>
        </div>
      </div>
    </div>
  </div>
</section>

<style>
  .skins {
    padding-block: 6rem;
    background-image: url(/haarlem-flipped.jpg);
    background-size: cover;
    background-position: center;
  }

  .hero-content {
    max-width: 32rem;
    display: grid;
    justify-items: start;
    gap: 1.5rem;
    padding: 3rem;
    border-radius: 1rem;

    & * {
      margin: 0;
    }
  }
</style>