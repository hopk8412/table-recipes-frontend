<script>
</script>

<footer class="footer">
  <nav class="navbar">
    <div class="navbar-inner">
      <a href="/recipes" class="logo nav-link">Recipes</a>
      <a href="/about" class="nav-link">About</a>
      <a href="/contact" class="nav-link">Contact</a>
    </div>
  </nav>
</footer>

<style>
  @font-face {
    font-family: "Rodin";
    src: local(""), url("/fonts/FOTRodin%20Pro%20DB.otf") format("opentype");
  }
  * {
    font-family: "Rodin", "Helvetica Neue", sans-serif;
  }

  .navbar {
    overflow: hidden;
    background-color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .navbar a {
    color: black;
    text-align: center;
    display: inline-block;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
    margin: 0px auto;
  }

  .navbar a:hover {
    background: black;
    color: white;
  }

  .nav-link.active {
    background: black;
    color: white;
  }
</style>
