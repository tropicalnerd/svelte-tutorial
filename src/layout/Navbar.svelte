<script>
    import { Link } from 'svelte-routing';
</script>

<style>
</style>

<nav>
  <div class="nav-wrapper">
    <div class="container">
      <Link to='/'><span class="brand-logo left">Svelte Tutorial</span></Link>
      <ul id="nav-mobile" class="right">
        <li><Link to="/">Home</Link></li>
        <li><Link to="/about">About</Link></li>
      </ul>
    </div>
  </div>
</nav>