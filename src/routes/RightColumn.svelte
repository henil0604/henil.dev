<script>
	import AboutRC from './About.RC.svelte';
	import TimelineRC from './Timeline.RC.svelte';
</script>

<div class="pt-0 pb-16 lg:pt-32 lg:w-1/2 flex flex-col">
	<AboutRC />
	<div class="my-3"></div>
	<TimelineRC />
	<div class="my-12"></div>
	<hr class="mb-4" />
	<div class="text-sm">
		<div>
			Built with
			<a target="_blank" class="underline" href="https://kit.svelte.dev"
				>SvelteKit</a
			>
		</div>
		<div>
			Deployed with
			<a target="_blank" href="https://vercel.com" class="underline"
				>Vercel</a
			>
		</div>
	</div>
</div>
