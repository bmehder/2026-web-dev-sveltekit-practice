<script>
	import DarkLogo from '$lib/assets/logo-dark.svg'
</script>

<header>
  <div class="skins">
    <div class="container">
      <div class="layout spread-apart">
        <div class="logo">
          <a href="/"><img src={DarkLogo} alt="dark logo"></a>
        </div>
        <nav>
          <ul class="spread-apart list-style-none gap-2">
            <li><a href="/">Home</a></li>
            <li><a href="/about">About</a></li>
            <li><a href="/portfolio">Portfolio</a></li>
            <li><a class="button bg-blue white svelte-ralae9" href="/contact">Contact</a></li>
          </ul>
        </nav>
      </div>
    </div>
  </div>
</header>

<style>
	.container {
		padding-block: 1rem;
	}

  ul {
    padding: 0;
    justify-content: start;
  }
</style>