<script>
  import Head from '@components/head.svelte'

  export let data
  let { copy } = data
</script>

<Head title={`Generator`} />

<h1 class="font-bold mb-5 text-5xl">Generator</h1>
<div class="mb-10 all-prose">
  
</div>

<div class="flex flex-col mb-20 w-full">
  <div class="divider" ></div>
  <textarea placeholder="Enter prompt" class="textarea textarea-bordered textarea-lg w-20px" ></textarea>
  
  <button class="btn rounded w-20px my-4">Enter</button>

</div>
