<script lang="ts">
	import '../app.css';
	import Navbar from '../components/Navbar.svelte';
	import ScrollToTop from '../components/ScrollToTop.svelte';
</script>

<Navbar />

<div class="flex flex-col lg:flex-row gap-12 items-center justify-center p-12 mb-12 bg-[#EDFDF2]" id="section-1">
	<div class="flex flex-col gap-12 items-center">
		<h1 class="text-4xl font-extrabold text-green-700">Finance Website</h1>
		<p>Finance is really important, here is why:</p>
		<p>
			Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolorem dicta quos magnam aliquam
			pariatur asperiores rerum blanditiis, incidunt velit provident rem soluta alias inventore
			delectus laborum, necessitatibus, ab omnis! Dignissimos.
		</p>
	</div>
	<img src="/images/graph.jpg" alt="" class="w-[640px] rounded" />
</div>
<ScrollToTop/>
<div class="flex flex-col gap-12 items-center justify-center p-12 mb-12 bg-[#FEFDF9]" id="section-2">
	<h1 class="text-4xl font-extrabold text-green-700">section 2</h1>
	<div class="flex flex-col lg:flex-row gap-12 items-center">
		<img src="/images/graph-2.jpg" alt="" class="w-[640px] rounded" />
		<div class="flex-col gap-12 flex items-center">
			<p>
				Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolorem dicta quos magnam aliquam
				pariatur asperiores rerum blanditiis, incidunt velit provident rem soluta alias inventore
				delectus laborum, necessitatibus, ab omnis! Dignissimos.
			</p>
		</div>
	</div>
</div>
<div class="flex flex-col gap-12 items-center justify-center h-screen p-12 bg-[#EDFDF2]" id="reviews">
	<h1 class="text-4xl font-extrabold text-green-700">What people think of us</h1>
	<p>
		reviews
	</p>
</div>
<div class="flex flex-col gap-12 items-center justify-center h-screen p-12 bg-[#FEFDF9]" id="prices">
	<h1 class="text-4xl font-extrabold text-green-700">Our prices</h1>
	<p>
		prices
	</p>
</div>
