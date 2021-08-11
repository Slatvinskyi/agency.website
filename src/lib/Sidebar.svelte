<script>
	export let open = false
</script>

<aside class="absolute w-72 h-full bg-gradient-to-r from-gray-900 via-gray-800 to-gray-900" class:open>
	<nav class="p-12 text-xl text-gray-500">
		
		<a class="block hover:text-gray-700 hover:no-underline" href="/">Home</a>
		<a class="block hover:text-gray-700 hover:no-underline" href="/contact">Contact</a>
		<a class="block hover:text-gray-700 hover:no-underline" href="/services">Services</a>
		<a class="block hover:text-gray-700 hover:no-underline" href="/about">About</a>
	</nav>
</aside>

<style>
	aside {
		left: -100%;
		transition: left 0.3s ease-in-out
	}
	
	.open {
		left: 0
	}
</style>