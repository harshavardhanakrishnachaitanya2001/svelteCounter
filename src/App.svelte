<script>
	let count=0;
	const increment=()=>{
		count+=1;
	}
</script>

<div class='main'>
	<h1>Counter</h1>
	<h2>Created by Harshavardhan using svelte</h2>
	<button on:click={increment}>Counter button clicked {count} {count===1? 'time': 'times'}</button>
</div>
<style>
	h1{
		text-align: center;
		font-size: 3.5rem;
	}
	h2{
		text-align: center;
	}
	button{
		display: block;
		margin-right: auto;
		margin-left: auto;
		cursor:pointer;
	}
</style>