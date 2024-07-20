<div class="centre">
  <article>
    <slot />
  </article>
</div>

<style>
  .centre {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  article {
    max-width: 1000px;
  }
</style>
