<script>
	import Navbar from './Navbar.svelte';
	import Expenses from './ExpenseList.svelte';
	import expensesData from './expenses';

	let expenses = [...expensesData];
</script>

<Navbar />
<main class="content">
	<Expenses {expenses} />
</main>