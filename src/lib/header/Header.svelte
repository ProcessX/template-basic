<script>
  import { page } from "$app/stores";
  import Navbar from "./navbar/Navbar.svelte";
</script>

<header
  class="w-screen flex justify-between py-2 px-4 border-b-2 border-gray-100 fixed top-0 left-0 bg-white"
>
  <Navbar />
  <!--
	<nav>
		<ul>
			<li class:active={$page.url.pathname === '/'}><a sveltekit:prefetch href="/">Home</a></li>
			<li class:active={$page.url.pathname === '/about'}>
				<a sveltekit:prefetch href="/about">About</a>
			</li>
			<li class:active={$page.url.pathname === '/todos'}>
				<a sveltekit:prefetch href="/todos">Todos</a>
			</li>
		</ul>
	
	</nav>
-->
</header>

<style>
</style>
