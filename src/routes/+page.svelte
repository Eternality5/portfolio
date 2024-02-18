<script>
	import {Avatar} from "@skeletonlabs/skeleton"
</script>

<svelte:head>
	<title>Home</title>
	<meta name="Home Page" content="Portfolio website for Maximilien Schuller" />
</svelte:head>

<section class="text-middle mx-10 text-center">
	<div class="flex justify-center py-2">
		<Avatar src="avatar.jpg" width="w-64" rounded="rounded-full" initials="MS" />
	</div>
	<div class="py-2">
		<h1 class="h1">MAXIMILIEN SCHULLER</h1>
	</div>
	<div class="py-2">
		<p>
			Hey there! I'm Max, a full-stack developer based in Adelaide with experience working with Java Spring Boot and
			React with TypeScript.
		</p>
	</div>
	<div class="flex justify-center">
	<div class="fit-content logo-cloud grid-cols-1 gap-1 lg:!grid-cols-2 max-w-full justify-center">
		<a class="logo-item p-4" href="https://github.com/Eternality5">
			<img src="github.svg" alt="Github Logo" />
			<span>Github</span>
		</a>
		<a class="logo-item p-4" href="https://www.linkedin.com/in/maximilien-schuller-477454174/">
			<img src="linkedin.svg" alt="Linkedin Logo" />
			<span>Linkedin</span>
		</a>
	</div>
</div>
</section>

<!-- <section>
	<h2 class="h2">My Projects</h2>

	<div class="grid grid-cols-1 lg:!grid-cols-3 content-start gap-4">
		<a href="https://github.com/Eternality5/g1-serp2023" class="card p-4">
			<header class="card-header">Deidentification Framework</header>
			<section class="p-4">content</section>
			<footer class="card-footer">By Max Schuller & Vinay Kumar</footer>
		</a>

		<a href="https://github.com/Eternality5/g1-serp2023" class="card p-4">
			<header class="card-header">header</header>
			<section class="p-4">content</section>
			<footer class="card-footer">footer</footer>
		</a>

		<a href="https://github.com/Eternality5/g1-serp2023" class="card p-4">
			<header class="card-header">header</header>
			<section class="p-4">content</section>
			<footer class="card-footer">footer</footer>
		</a>
	</div>
</section> -->
