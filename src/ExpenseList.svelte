<script>
    import Title from './Title.svelte';
    import Expense from './Expense.svelte';
    export let expenses = [];
</script>

<Title title="Expense List" />
<ul>
    {#each expenses as expense}
        <Expense {expense} />
    {/each}
</ul>