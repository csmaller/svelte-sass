<script>
import About from "./about.svelte";
  export let name;
</script>
<!-- can we import scss like this?  sure can. -->
<style src="./main.scss"></style>

<h1>Hello {name}!</h1>

<div>
  <p>SASS is working!</p>
  <About name={name} />
</div>
