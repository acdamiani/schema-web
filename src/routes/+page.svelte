<script lang="ts">
	import Logo from '$lib/svg/Logo.svelte';
	import CodeSnippet from './components/CodeSnippet.svelte';
	import NodeSvg from './components/NodeSVG.svelte';
	import Tree from '$lib/svg/Tree.svelte';
</script>

<div class="ml-16 pt-4">
	<Logo />
</div>

<div class="flex justify-center px-8 md:px-40">
	<div class="max-w-screen-xl flex flex-col-reverse lg:flex-row items-center gap-2 md:gap-6">
		<div class="flex flex-col flex-shrink-0 gap-4 items-center lg:items-start">
			<h1 class="font-head text-3xl md:text-5xl font-bold">Create AI with ease</h1>
			<div class="flex gap-4">
				<a
					class="rounded-full bg-black hover:bg-neutral-800 transition-colors px-4 py-2 text-white font-semibold flex gap-2 items-center group"
					href="https://assetstore.unity.com/packages/tools/behavior-ai/schema-200876"
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
				</a>

				<a
					class="rounded-full border-black hover:bg-neutral-100 transition-colors border-2 px-4 py-2 text-black font-semibold flex gap-2 items-center group"
					href="https://github.com/acdamiani/schema"
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
				</a>
			</div>
			<span class="text-sm text-neutral-500">Supports Unity 2021.3 and higher</span>
		</div>
		<img src="/img/hero-image.png" alt="hero" width="750px" />
	</div>
</div>

<section class="mt-12">
	<div class="flex justify-center w-full px-8 md:px-40">
		<div class="max-w-screen-xl grid grid-rows-3 md:grid-rows-none md:grid-cols-3 gap-8">
			<div class="flex flex-col gap-3">
				<h3 class="font-head text-3xl font-semibold">Extendable</h3>
				<p class="text-lg">
					Schema's powerful API allows you to extend the existing library of 150+ nodes with just a
					few lines of code.
				</p>
			</div>
			<div class="flex flex-col gap-3">
				<h3 class="font-head text-3xl font-semibold">Performant</h3>
				<p class="text-lg">
					Schema's data-oriented design results in blazing fast speed — all with zero runtime
					garbage collector allocations.
				</p>
			</div>
			<div class="flex flex-col gap-3">
				<h3 class="font-head text-3xl font-semibold">Intuitive</h3>
				<p class="text-lg">
					Powerful shortcuts, a quick action menu, and a beautiful interface lets you skip the hard
					stuff.
				</p>
			</div>
		</div>
	</div>
</section>

<section class="mt-12 bg-zinc-100 py-8 px-8 md:px-40">
	<div class="flex flex-col md:flex-row items-center">
		<div class="flex flex-col gap-3 max-w-sm">
			<h3 class="font-head text-3xl font-semibold">Quick and easy.</h3>
			<p class="text-lg">
				Author nodes just like your components&mdash;a Unity-like API makes learning easy and
				creating fast.
			</p>
		</div>
		<div
			class="relative grid grid-flow-col md:grid-flow-row grid-rows-2 md:grid-rows-none md:grid-cols-2 gap-y-4 items-center justify-items-center w-full"
		>
			<h4 class="font-head text-2xl">Here's a node...</h4>
			<h4 class="font-head text-2xl">...and here's the code</h4>
			<div class="drop-shadow-lg">
				<NodeSvg />
			</div>
			<div class="flex flex-col rounded-lg shadow-lg" style="background-color: #2E3440;">
				<div class="flex gap-2 px-3 py-4 border-b border-slate-400">
					<div class="rounded-full w-3 h-3 bg-slate-400" />
					<div class="rounded-full w-3 h-3 bg-slate-400" />
					<div class="rounded-full w-3 h-3 bg-slate-400" />
				</div>
				<div class="px-4 py-3">
					<CodeSnippet />
				</div>
			</div>
		</div>
	</div>
</section>

<section
	class="py-12"
	style="background-size: 16px 16px;
    background-image: linear-gradient(to right, #383838 1px, transparent 1px),
    linear-gradient(to bottom, #383838 1px, transparent 1px);
    background-color: #282828;"
>
	<div class="flex flex-col items-center w-full gap-8">
		<h3 class="font-head text-3xl font-semibold text-white">The Behavior Tree</h3>
		<Tree />
	</div>
</section>

<section class="pt-4 flex justify-center">
	Made with ❤️ by&nbsp;<a class="text-blue-600" href="https://www.linkedin.com/in/augustdamiani/"
		>August Damiani</a
	>
</section>
