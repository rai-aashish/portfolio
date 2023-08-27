<script>
	import { page } from '$app/stores';
</script>

<header class="flex justify-center items-center py-5">
	<nav class="">
		<ul class="nav-links flex items-center justify-center">
			<li aria-current={$page.url.pathname === '/' ? 'page' : undefined} >
				<a href="/">Home</a>
			</li>
			<li aria-current={$page.url.pathname === '/about' ? 'page' : undefined} >
				<a href="/about">About</a>
			</li>
		</ul>
	</nav>
</header>

<style scoped>
	.nav-links li[aria-current="page"]{
		background-image:linear-gradient(83.84deg, #0088FF -6.87%, #A033FF 26.54%, #FF5C87 58.58%);
		-webkit-background-clip: text;
  		-webkit-text-fill-color: transparent;
		@apply p-2 rounded text-white ;
	}
</style>