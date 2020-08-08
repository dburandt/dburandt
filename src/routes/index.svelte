<script>
  import Error from "./_error.svelte";
</script>

<style>
  p {
    text-align: center;
    margin: 1em auto;
  }

  div {
    display: grid;
    grid-template-columns: 500px;
    justify-content: center;
    margin-top: 22px;
  }

  a {
    display: block;
  }

  img {
    width: 22px;
    margin-top: 8px;
  }
</style>

<svelte:head>
  <title>Derek's Site</title>
</svelte:head>

<div>
  <p>
    Hello, my name is
    <strong>Derek Burandt</strong>
    and this is my personal webpage. I'm a software developer based out of
    Toronto Ontario, 🇨🇦. Stay tuned for some future blog posts! Until then,
    here's my github:
    <a href="https://github.com/dburandt">
      <img src="github-icon.png" alt="github" />
    </a>
  </p>
</div>
