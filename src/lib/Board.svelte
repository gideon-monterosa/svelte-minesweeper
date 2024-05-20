<script lang="ts">
  const tiles = [['', ''], ['', '']];
</script>

<div class="flex">
  {#each tiles as row}
    <div>
      {#each row as tile}
        <div class="bg-gray-400 h-8 w-8 m-1">
          {tile}
        </div>
      {/each}
    </div>
  {/each}
</div>
