<script lang="ts">
	import '../../app.css';
	import Docs from '../docs.svelte';

	let curl = '{}';
</script>

<Docs />

<div class="ml-6 mt-6 bg-gray-800 mb-5">
	<h1 class="text-gray-100 text-2xl font-bold mb-7">
		<big> Let's create a variable </big>
	</h1>
	<p class="text-gray-100">
		To create a variable velt lang uses the <span class="font-bold">go</span> keyword
	</p>
</div>
<pre
	class="ml-6 mb-5 grid h-screen place-items-center language-html px-auto bg-gray-100 rounded-md h-[50px] w-[350px]"><code
		class="dark:hidden language-html font-sans font-bold"
		><span class="text-blue-500">go </span><span class="text-[#fcd34d]">a </span><span
			class="text-[#fb923c]"
			>str </span>=<span class="text-green-500"> "Hello World"</span></code
	></pre>
<pre
	class="ml-6 mb-5 grid h-screen place-items-center language-html px-auto bg-gray-100 rounded-md h-[50px] w-[350px]"><code
		class="dark:hidden language-html font-sans font-bold"
		><span class="text-blue-500">go </span><span class="text-[#fcd34d]">a </span><span
			class="text-[#fb923c]"
			>i32 </span>=<span class="text-green-500"> 9</span></code
	></pre>
<pre
	class="ml-6 grid h-screen place-items-center language-html px-auto bg-gray-100 rounded-md h-[50px] w-[350px]"><code
		class="dark:hidden language-html font-sans font-bold"
		><span class="text-blue-500">go </span><span class="text-[#fcd34d]">a </span><span
			class="text-[#fb923c]"
			>u32 </span>=<span class="text-green-500"> 10</span></code
	></pre>

<p class="text-gray-100 ml-6 mt-6">There a 3 types in velt lang:</p>
<ul class=" text-gray-100 ml-8 mt-6">
	<li>str</li>
	<li>i32</li>
	<li>u32</li>
</ul>
<p />
<div class="ml-6 mt-6 bg-gray-800 mb-5">
	<h1 class="text-gray-100 text-2xl font-bold mb-7">
		<big> Let's print it </big>
	</h1>
	<p class="text-gray-100">
		At velt lang The deafault specifier for variable is <span class="text-[#fcd34d] font-sans"
			>v$</span
		>
	</p>
</div>
<pre
	class="ml-6 grid h-screen place-items-center language-html px-auto bg-gray-100 rounded-md w-[350px]"><code
		class="dark:hidden language-html font-sans font-bold"
		><span class="text-blue-500">write </span><span class="text-[#fcd34d]">{curl}, </span><span
			class="text-[#fb923c]">v$</span
		><span class="text-green-500">a</span></code
	></pre>
