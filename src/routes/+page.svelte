<div class="container">
	<h1 class="title">Welcome to SvelteKit</h1>
	<p>
		Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation
	</p>
</div>

<style lang="postcss">
	/* ตัวอย่างการใช้งาน tailwind ใน style ของ .svelte */
	@reference "tailwindcss/theme";
	@plugin "daisyui";

	.container {
		@apply px-4 py-2;
	}

	.title {
		@apply text-transparent font-bold text-4xl bg-gradient-to-r from-primary from-5% to-pink-500 to-40% bg-clip-text;
	}
</style>
