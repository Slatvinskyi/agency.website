<script>
	
	import Sidebar from '$lib/Sidebar.svelte'
	import Navbar from '$lib/Navbar.svelte'

	let open = false
</script>

<Sidebar bind:open/>
<Navbar bind:sidebar={open}/>


<svelte:head>
	<link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet"/>
</svelte:head>

<style>
	:global(body) {
		padding: 0;
	}
</style>