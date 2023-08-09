<script lang="ts">
	export let data;
	import '../app.css';
</script>

<p class="bg-black text-sky-500">
	{#await data.streamed.views}
		Loading...
	{:then views}
		This page has been viewed {views} times.
	{:catch error}
		{error.message}
	{/await}
</p>
