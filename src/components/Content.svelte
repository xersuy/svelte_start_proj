<script>
  import SubContent from "./SubContent.svelte";
  let count = 0;

  const handleClick = () => {
    count++;
    console.log(count);
  };
</script>

<p>Content Space</p>
<button on:click={handleClick}>
  클릭수 {count}
</button>
<SubContent />
<SubContent />
<SubContent />
<SubContent />
<SubContent />
