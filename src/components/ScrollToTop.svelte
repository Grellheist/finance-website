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
	class="fixed rounded-full right-[20px] bottom-[20px] bg-black text-white p-2"
	on:click={goStart}
	class:hidden
>
	Back To Start
</div>
