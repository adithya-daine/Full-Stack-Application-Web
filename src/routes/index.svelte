<script>
	import TodoItems from '$lib/todo-items.svelte';

	const title = 'Todo';
</script>

<svelte:head>
	<title>{title}</title>
</svelte:head>

<h1>{title}</h1>

<!--Creating a form-->
<form action="" method="">
	<input
		type="text"
		name="text"
		value=""
		aria-label="Add a todo"
		placeholder="+ tap to add a todo"
	/>
</form>

<!--Svelte components-->
<TodoItems />
