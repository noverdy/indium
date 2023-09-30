<script>
	import '@fortawesome/fontawesome-free/css/all.min.css';
	import '../app.css';
</script>

<svelte:head>
	<title>Indium | E2E Chat App</title>
</svelte:head>

<div class="fixed inset-0 [&>*]:overflow-auto">
	<slot />
</div>
