<script lang="ts">
  import '$src/app.css';
</script>

<svelte:head>
  <title>My App</title>
</svelte:head>

<header class="primary"></header>
<div id="wrap">
  <div class="hscreen p-5" id="content">
    <slot />
  </div>
</div>
<footer class="primary"></footer>


<style lang="postcss">
#content{
  overflow: auto;
  overflow-x: hidden;
  position: relative;
}

#wrap {
  min-height: 100vh;
  padding: 0;
}
</style>
