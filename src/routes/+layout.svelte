<script>
	import '../app.css';
</script>

<article class="container mx-auto flex flex-col items-center gap-5 py-20">
	<slot />
</article>

<style type="postcss">
	:global(body) {
		@apply bg-slate-800 text-white;
	}
</style>
