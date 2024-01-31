<script lang="ts">
	import Header from '$lib/components/Header.svelte';
	import Sidebar from '$lib/components/Sidebar.svelte';
	import './style.css';
</script>

<Header />
<div class="flex">
	<Sidebar />
	<main class="ml-[74px] flex-1 p-6">
		<slot />
	</main>
</div>
