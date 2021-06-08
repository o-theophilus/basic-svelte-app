<nav>
	<div class="block">
		<a href="/">Home</a>
		<a href="/about">About</a>
		<a href="/contact">Contact</a>
	</div>
</nav>

<section>
	<div class="block">
		<slot />
	</div>
</section>

<footer>
	<div class="block">
		<p>Thank you for visiting my awesome app.</p>
	</div>
</footer>

<style>
	.block {
		max-width: 800px;

		margin: auto;
		padding: 20px 40px;
	}
	nav {
		background-color: bisque;
	}
	section {
		background-color: lightgrey;
	}
	section .block {
		background-color: white;
		min-height: calc(100vh - 210px);
	}

	footer {
		background-color: black;
		color: white;
	}
</style>
