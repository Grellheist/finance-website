<script>
	let showMenu = false;
	function toggleNavbar() {
		showMenu = !showMenu;
	}
</script>

<nav
	class="bg-[#EDFDF2] select-none w-full flex justify-between items-center h-28 z-50"
	class:open={showMenu}
>
	<a href="/">
		<h1 class="text-lg pl-4 lg:pl-8">Finance Website</h1>
	</a>
	<div class="hidden lg:flex gap-12">
		<a href="#millionare" class="group hover:text-green-700 transition duration-300 font-semibold">
			Become a Millionare
			<span
				class="block max-w-0 group-hover:max-w-full rounded-full transition-all duration-300 h-0.5 bg-green-700"
			/>
		</a>
		<a href="#tutorial" class="group hover:text-green-700 transition duration-300 font-semibold">
			How to make money
			<span
				class="block max-w-0 group-hover:max-w-full rounded-full transition-all duration-300 h-0.5 bg-green-700"
			/>
		</a>
		<a href="#reviews" class="group hover:text-green-700 transition duration-300 font-semibold">
			Our reviews
			<span
				class="block max-w-0 group-hover:max-w-full rounded-full transition-all duration-300 h-0.5 bg-green-700"
			/>
		</a>
		<a href="#prices" class="group hover:text-green-700 transition duration-300 font-semibold">
			Our prices
			<span
				class="block max-w-0 group-hover:max-w-full rounded-full transition-all duration-300 h-0.5 bg-green-700"
			/>
		</a>
	</div>
	<div class="hidden lg:flex pr-8 gap-12 items-center">
		<a href="/login" class="group hover:text-green-700 transition duration-300 font-semibold"
			>Login
			<span
				class="block max-w-0 group-hover:max-w-full rounded-full transition-all duration-300 h-0.5 bg-green-700"
			/>
		</a>
		<a
			href="/register"
			class="rounded-lg ease-in-out duration-300 font-semibold py-3 px-6 text-white bg-green-700 hover:bg-green-800"
			>Register</a
		>
	</div>
	<div
		class="lg:hidden pr-4 lg:pr-8 cursor-pointer"
		on:click={toggleNavbar}
		role="button"
		tabindex="0"
		on:keypress={toggleNavbar}
	>
		<button aria-label="Hamburger Button" type="button" class="p-2 inline-flex text-green-700 focus:outline-none">
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
		class="bg-[#EDFDF2] pb-12 shadow-sm shadow-black absolute z-30 top-0 inset-x-0 p-2 flex-col gap-6 transition transform origin-top-right lg:hidden opacity-100 scale-100 {showMenu
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
				<button type="button" aria-label="Close Button" class="p-2 inline-flex focus:outline-none">
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
			<a href="#millionare" class="" on:click={() => (showMenu = false)}> Become a Millionare </a>
			<a href="#tutorial" class="" on:click={() => (showMenu = false)}> How to make money </a>
			<a href="#reviews" class="" on:click={() => (showMenu = false)}> Our reviews </a>
			<a href="#prices" class="" on:click={() => (showMenu = false)}> Our prices </a>
		</div>
		<div class="">
			<a
				href="/register"
				on:click={() => (showMenu = false)}
				class="rounded-lg ease-in-out duration-300 w-full flex justify-center font-semibold py-3 px-6 text-white bg-green-700 hover:bg-green-800"
				>Start now!</a
			>
		</div>
	</div>
</nav>
