<script lang="ts">
  export let selected: string;
</script>

<div class="menu-bar">
  <a href="/" class="home menu-item {selected === 'home' ? 'selected' : ''}">
    <img class="menu-logo" src="/favicon.png" alt="Bizfork logo" />
    <h1>{selected === 'home' ? 'Home' : 'Bizfork'}</h1>
  </a>
  <a href="/success-stories" class="menu-item {selected === 'success-stories' ? 'selected' : ''}">
    <h1>Success stories</h1>
  </a>
</div>

<style>
  .menu-bar {
    display: flex;
    width: 100%;
    justify-content: center;
    gap: 30px;
    margin: 25px;
  }

  .home {
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .home > h1 {
    margin: 0;
  }

  .menu-logo {
    height: 2rem;
  }

  .menu-item {
    color: black;
    text-decoration: none;
    background-color: antiquewhite;
    padding: 10px;
    border-radius: 30px;
  }

  .menu-item:hover {
    background-color: bisque;
  }

  .selected {
    background-color: salmon;
  }
  .selected:hover {
    background-color: coral;
  }
</style>
