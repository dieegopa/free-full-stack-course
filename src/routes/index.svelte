<script lang="ts">
	import TodoItem from '$lib/todoItem.svelte';

	const title = 'Todos';
</script>

<svelte:head>
	<title>{title}</title>
</svelte:head>

<h1>{title}</h1>

<form action="" method="">
	<input type="text" name="text" aria-label="Add a todo" placeholder="+ tap to add a todo" />
</form>

<TodoItem />
<TodoItem />
<TodoItem />

<style>
</style>
