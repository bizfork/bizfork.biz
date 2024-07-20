<script>
    import Menu from "$lib/Menu.svelte";

</script>
<svelte:head>
  <title>Bizfork - B2B solutions for a late-stage-capitalism world</title>
</svelte:head>

<Menu selected="home" />

<div>
  <img class="header-img" src="/favicon.png" alt="Bizfork logo" />

  <h1>Bizfork</h1>

  <em>
    We help businesses develop the problems they need for the solutions they
    create.
  </em>
</div>

<img class="footer-img" src="/business-people-cheering.png" alt="business people cheering" />

<style>
  div {
    margin: 0 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  h1 {
    margin-top: 0px;
    font-size: 10rem;
  }

  @media (max-width: 600px) {
    h1 {
      font-size: 25vw;
    }
  }

  em {
    font-size: 2rem;
    padding: 30px 0px;
  }

  .header-img {
    max-width: 70%;
  }

  .footer-img {
    width: 100%;
  }
</style>
