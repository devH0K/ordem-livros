<script lang="ts">
  export let serie: any = null;
</script>
{#if serie}
  <div>
    {serie.id}
  </div>  
{/if}