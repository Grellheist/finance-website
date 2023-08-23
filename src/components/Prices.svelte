<script lang="ts">
	export let name: string, price: number, benefits: string[], notIncluded: string[];
</script>

<div class="w-full bg-green-200 p-10 rounded-xl shadow-xl hover:scale-105 transition duration-300 group">
	<h4 class="mb-4 text-2xl font-medium text-gray-600 flex justify-center">{name}</h4>
	<div class="flex items-baseline justify-center">
		<span class="text-3xl font-semibold">$</span>
		<span class="text-7xl font-extrabold">{price}</span>
		<span class="text-xl ml-1 font-normal text-gray-600">/month</span>
	</div>
	<ul class="space-y-5 my-7">
		{#each [...benefits] as benefit}
			<li class="flex space-x-3">
				<i class="bi bi-check-circle-fill text-green-700" />
				<span class="leading-tight text-gray-600">
					{benefit}
				</span>
			</li>
		{/each}
		{#each [...notIncluded] as item}
			<li class="flex space-x-3 line-through decoration-gray-700">
				<i class="bi bi-check-circle-fill text-gray-700" />
				<span class="leading-tight text-gray-600">
					{item}
				</span>
			</li>
		{/each}
	</ul>
	<button
		class="bg-green-700 text-white transition-all rounded-lg text-lg p-2 w-full group-hover:bg-green-800"
		>Choose Plan</button
	>
</div>
