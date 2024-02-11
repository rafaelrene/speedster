<div class="wrapper grid gap-x-2">
	<div class="h-12 w-12 rounded-lg bg-slate-200 [grid-area:logo]">1</div>

	<h1 class="text-xl font-bold text-rose-600 [grid-area:headline]">Speedster</h1>
	<h2 class="text-sm text-slate-500 [grid-area:description]">
		Change YouTube playback speed globally
	</h2>
</div>

<style>
	.wrapper {
		grid-template:
			'logo headline'
			'logo description';
		grid-template-columns: 3rem 1fr;
	}
</style>
