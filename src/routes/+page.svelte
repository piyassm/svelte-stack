<script>
    import TodoItem from "$lib/components/todo-item.svelte";
    const title = "Todo";
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>
<h1>Welcome to SvelteKit Todo</h1>

<form action="" method="">
    <input
        type="text"
        name="text"
        aria-label="Add a todo"
        placeholder="Add a todo"
    />
</form>

<TodoItem />
