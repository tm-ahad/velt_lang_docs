<script lang="ts">
	import '../../app.css';
	import Docs from '../docs.svelte';

	let curl = '{}';
</script>

<Docs />

<div class="ml-6 mt-6 bg-gray-800 mb-5">
	<h1 class="text-gray-100 text-2xl font-bold mb-7">
		<big> What is formatter? </big>
	</h1>
	<p class="text-gray-100">
		velt lang has formatter like <span class="font-bold text-green-500">Rust</span>, go, c, c++,
		python and javascript. A formatter is in which format the value will printed.
	</p>
	<p class="text-gray-100">
		velt lang follows <span class="font-bold text-green-500">Rust</span> formatters
	</p>
</div>
<div class="ml-6 mt-6 bg-gray-800 mb-5">
	<h1 class="text-gray-100 text-2xl font-bold mb-7">
		<big> Let's see! </big>
	</h1>
</div>

<pre
	class="ml-6 grid place-items-center language-html px-auto bg-gray-100 rounded-md h-[110px] w-[350px]">
   <code class="dark:hidden language-html font-sans font-bold"
		><span class="text-blue-500">write </span><span class="text-[#fcd34d]">str</span><span
			class="text-[#fb923c]"
			>{curl}, </span><span class="text-green-500">"Hello \nWorld"</span></code
	>
   <code class="py-0 dark:hidden language-html font-sans font-bold"
		><span class="text-blue-500">write </span><span class="text-[#fcd34d]">str</span> <span
			class="text-[#fb923c]"
			>:?, </span><span class="text-green-500">"Hello \nWorld"</span></code
	>
   <code class="dark:hidden language-html font-sans font-bold"
		><span class="text-blue-500">write </span><span class="text-[#fcd34d]">str</span> <span
			class="text-[#fb923c]"
			>:#?, </span><span class="text-green-500">"Hello \nWorld"</span></code
	>
</pre>

<div class="ml-6 mt-6 bg-gray-800 mb-5">
	<h1 class="text-gray-100 text-2xl font-bold mb-7">
		<big> Result: </big>
	</h1>
</div>

<pre class="language-html px-auto ml-6 bg-gray-100 rounded-md h-[185px] w-[350px]">
   <code class="dark:hidden language-html font-sans font-bold">
      Hello
      World</code
	>
   <code class="dark:hidden language-html font-sans font-bold">
      "Hello
      World"</code
	>
   <code class="dark:hidden language-html font-sans font-bold">"Hello \nWorld"</code>
</pre>
