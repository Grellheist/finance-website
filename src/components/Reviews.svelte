<script lang="ts">
	export let src: string, name: string, testimonial: string;
</script>

<div class="bg-green-200 p-8 rounded-xl space-y-12 max-w-[300px] shadow-xl hover:scale-105 transition duration-300">
	<img {src} alt="User's face" class="h-20 mx-auto rounded-full" loading="lazy" decoding="async" />
	<h4 class="uppercase text-xl font-bold">{name}</h4>
	<p class="text-md leading-7 my-3 font-light">
		{testimonial}
	</p>
</div>
