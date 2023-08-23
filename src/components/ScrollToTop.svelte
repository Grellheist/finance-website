<script>
	export let buttonVisibleOnPX = 200;
	let hidden = true;

	const goStart = () => {
		document.body.scrollIntoView();
	};

	const scrollElement = () => {
		return document.documentElement || document.body;
	};

	const handleOnScroll = () => {
		if (scrollElement().scrollTop > buttonVisibleOnPX) {
			hidden = false;
		} else {
			hidden = true;
		}
	};
</script>

<svelte:window on:scroll={handleOnScroll} />

<div
	role="button"
	tabindex="0"
	on:keypress={goStart}
	on:click={goStart}
	class:hidden
>
	<img src="/assets/up-arrow.svg" alt="" class="fixed select-none right-[20px] bottom-[20px] w-12 z-50">
</div>
