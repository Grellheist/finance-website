<script>
	let showMenu = false;
	function toggleNavbar() {
		showMenu = !showMenu;
	}
</script>

<nav class="select-none w-full flex justify-between items-center h-28 z-50" class:open={showMenu}>
	<a href="/">
		<h1 class="text-lg pl-4 lg:pl-8">Finance Website</h1>
	</a>
	<div class="hidden lg:flex gap-12">
		<a href="#section-1" class=""> Placeholder </a>
		<a href="#section-2" class=""> Placeholder </a>
		<a href="#section-3" class=""> Placeholder </a>
		<a href="#section-4" class=""> Placeholder </a>
	</div>
	<div class="hidden lg:flex pr-8 gap-12 items-center">
		<a href="/">Placeholder</a>
		<a
			href="/"
			class="rounded-lg ease-in-out duration-300 font-semibold py-3 px-6 text-white bg-green-700 hover:bg-green-800"
			>Placeholder</a
		>
	</div>
	<div
		class="lg:hidden pr-4 lg:pr-8 cursor-pointer"
		on:click={toggleNavbar}
		role="button"
		tabindex="0"
		on:keypress={toggleNavbar}
	>
		<button type="button" class="p-2 inline-flex text-green-700 focus:outline-none">
			<svg
				xmlns="http://www.w3.org/2000/svg"
				fill="none"
				viewBox="0 0 24 24"
				stroke-width="2"
				stroke="currentColor"
				class="w-8 h-8"
				aria-hidden="true"
			>
				<path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16" />
			</svg>
		</button>
	</div>
	<div
		class="absolute z-30 top-0 inset-x-0 p-2 flex-col gap-6 transition transform origin-top-right bg-white lg:hidden opacity-100 scale-100 {showMenu
			? 'flex'
			: 'hidden'}"
	>
		<div class="flex items-center mt-7 justify-between">
			<a href="/">
				<h1 class="text-lg pl-4 lg:pl-8">Finance Website</h1>
			</a>
			<div
				class="lg:hidden pr-4 lg:pr-8 cursor-pointer"
				on:click={toggleNavbar}
				role="button"
				tabindex="0"
				on:keypress={toggleNavbar}
			>
				<button type="button" class="p-2 inline-flex focus:outline-none">
					<svg
						xmlns="http://www.w3.org/2000/svg"
						fill="none"
						viewBox="0 0 24 24"
						stroke-width="2"
						stroke="currentColor"
						aria-hidden="true"
						class="h-7 w-7"
					>
						<path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
					</svg>
				</button>
			</div>
		</div>
		<div class="flex flex-col gap-6 justify-center items-center">
			<a href="#section-1" class="" on:click={() => (showMenu = false)}> Placeholder </a>
			<a href="#section-2" class="" on:click={() => (showMenu = false)}> Placeholder </a>
			<a href="#section-3" class="" on:click={() => (showMenu = false)}> Placeholder </a>
			<a href="#section-4" class="" on:click={() => (showMenu = false)}> Placeholder </a>
		</div>
		<div class="">
			<a
				href="/"
				on:click={() => (showMenu = false)}
				class="rounded-lg ease-in-out duration-300 w-full flex justify-center font-semibold py-3 px-6 text-white bg-green-700 hover:bg-green-800"
				>Placeholder</a
			>
		</div>
	</div>
</nav>
