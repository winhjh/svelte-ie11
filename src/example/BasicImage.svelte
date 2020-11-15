<script>
  export let src, alt, activeCondition;
  const active = activeCondition()
  console.log(active)
</script>

<img class:active {src} {alt}/>