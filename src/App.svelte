<script>
	import HelloWorld from './HelloWorld/index.svelte';
	import WriteSomething from './WriteSomething/index.svelte';
	import InputValue from './InputValue/index.svelte';
</script>

<main>
	<h1>Svelte</h1>
	<h2>Example 1 - hello world</h2>
		<HelloWorld/>
	<h2>Example 2 - write a custom text</h2>
		<WriteSomething something="Haha!"/>
	<h2>Example 3 - input value</h2>
		<InputValue/>
	<h2>Example 4 - transitions</h2>
<!--	<TransitionExample/>-->
	<h2>Example 5 - class binding</h2>
<!--	<ClassBindingExample/>-->
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
