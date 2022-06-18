<script>
  let polyrhythm = [2, 3];
</script>

<div class="d-flex justify-content-center">
  {#each polyrhythm as poly, i}
    <button class="btn btn-text" on:pointerdown={pointerDownHandler}>
      {poly}
    </button>

    {#if i < polyrhythm.length - 1}
      <button class="btn btn-text" disabled> : </button>
    {/if}
  {/each}
</div>

