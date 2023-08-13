<script lang="ts">
	import '../app.css';
	let showMenu = false;
	function toggleNavbar() {
		showMenu = !showMenu;
	}
</script>

<nav class="select-none w-full flex justify-between items-center h-28 z-50">
	<a href="/">
		<h1 class="text-lg pl-4 lg:pl-8">Finance Website</h1>
	</a>
	<div class="hidden lg:flex gap-12">
		<a href="#section-1" class=""> Placeholder </a>
		<a href="/" class=""> Placeholder </a>
		<a href="/" class=""> Placeholder </a>
		<a href="/" class=""> Placeholder </a>
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
		<button type="button" class="">
			<svg
				xmlns="http://www.w3.org/2000/svg"
				fill="none"
				viewBox="0 0 24 24"
				stroke-width="1.5"
				stroke="currentColor"
				class="w-6 h-6"
			>
				<path
					stroke-linecap="round"
					stroke-linejoin="round"
					d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
				/>
			</svg>
		</button>
	</div>
</nav>

<div class="flex flex-col gap-12 items-center justify-center h-screen p-12" id="section-1">
	<h1 class="text-4xl font-extrabold text-green-700">Finance Website</h1>
	<p>Finance is really important, here is why:</p>
	<p>
		Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolorem dicta quos magnam aliquam
		pariatur asperiores rerum blanditiis, incidunt velit provident rem soluta alias inventore
		delectus laborum, necessitatibus, ab omnis! Dignissimos.
	</p>
</div>
<div class="flex flex-col gap-12 items-center justify-center h-screen p-12" id="section-2">
	<h1 class="text-4xl font-extrabold text-green-700">section 2</h1>
	<p>Finance is really important, here is why:</p>
	<p>
		Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolorem dicta quos magnam aliquam
		pariatur asperiores rerum blanditiis, incidunt velit provident rem soluta alias inventore
		delectus laborum, necessitatibus, ab omnis! Dignissimos.
	</p>
</div>
<div class="flex flex-col gap-12 items-center justify-center h-screen p-12" id="section-3">
	<h1 class="text-4xl font-extrabold text-green-700">section 3</h1>
	<p>Finance is really important, here is why:</p>
	<p>
		Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolorem dicta quos magnam aliquam
		pariatur asperiores rerum blanditiis, incidunt velit provident rem soluta alias inventore
		delectus laborum, necessitatibus, ab omnis! Dignissimos.
	</p>
</div>
<div class="flex flex-col gap-12 items-center justify-center h-screen p-12" id="section-4">
	<h1 class="text-4xl font-extrabold text-green-700">section 4</h1>
	<p>Finance is really important, here is why:</p>
	<p>
		Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolorem dicta quos magnam aliquam
		pariatur asperiores rerum blanditiis, incidunt velit provident rem soluta alias inventore
		delectus laborum, necessitatibus, ab omnis! Dignissimos.
	</p>
</div>
