<script>
  export let src;

  function onError(){
    this.style.display='none';
  }
</script>

<style>
  .poster {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
</style>

<img {src} class="poster" alt="poster" onerror="onError()" />
