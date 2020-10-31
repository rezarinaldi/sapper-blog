<script>
  export let tags;
</script>

<style>
  nav {
    display: flex;
    gap: 4px;
  }
</style>

<nav>
  {#each tags as tag}<a href="/tag/{tag}">#{tag}</a>{/each}
</nav>
