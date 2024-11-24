<script lang="ts">
  export let autor:any = null;
</script>
{#if autor}
<div class="flex flex-col gap-5">
  <img src={autor.imagem} alt="Foto do Autor" class="h-96 object-cover rounded-md">
  <article>
    {autor.biografia}
  </article>
</div>
{/if}