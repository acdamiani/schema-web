<script>
	import Logo from '$lib/svg/Logo.svelte';
</script>

<div class="max-h-8 pt-4">
	<Logo />
</div>

<div class="flex flex-col-reverse lg:flex-row items-center gap-0 md:gap-6">
	<div class="flex flex-col flex-shrink-0 gap-4 items-center lg:items-start">
		<h1 class="font-head text-5xl font-semibold">Create AI with ease</h1>
		<div class="flex gap-4">
			<button
				class="rounded-full bg-black hover:bg-neutral-800 transition-colors px-4 py-2 text-white font-semibold flex gap-2 items-center group"
				>Download for free

				<svg
					class="transition-transform group-hover:translate-x-0.5"
					xmlns="http://www.w3.org/2000/svg"
					height="1em"
					viewBox="0 0 320 512"
					><path
						d="M278.6 233.4c12.5 12.5 12.5 32.8 0 45.3l-160 160c-12.5 12.5-32.8 12.5-45.3 0s-12.5-32.8 0-45.3L210.7 256 73.4 118.6c-12.5-12.5-12.5-32.8 0-45.3s32.8-12.5 45.3 0l160 160z"
						fill="white"
					/></svg
				>
			</button>

			<button
				class="rounded-full border-black hover:bg-neutral-100 transition-colors border-2 px-4 py-2 text-black font-semibold flex gap-2 items-center group"
				>View source

				<svg
					class="transition-transform group-hover:translate-x-0.5"
					xmlns="http://www.w3.org/2000/svg"
					height="1em"
					viewBox="0 0 320 512"
					><path
						d="M278.6 233.4c12.5 12.5 12.5 32.8 0 45.3l-160 160c-12.5 12.5-32.8 12.5-45.3 0s-12.5-32.8 0-45.3L210.7 256 73.4 118.6c-12.5-12.5-12.5-32.8 0-45.3s32.8-12.5 45.3 0l160 160z"
					/></svg
				>
			</button>
		</div>
		<span class="text-sm text-neutral-500">Supports Unity 2021.3 and higher</span>
	</div>
	<img src="/img/hero-image.png" alt="hero" width="750px" />
</div>
