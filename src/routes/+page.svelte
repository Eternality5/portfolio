<script>
	import { Avatar } from '@skeletonlabs/skeleton';
	import ProjectCard from './ProjectCard.svelte';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="Home Page" content="Portfolio website for Maximilien Schuller" />
</svelte:head>

<section class="p-10 text-center">
	<div class="flex justify-center py-2">
		<Avatar src="avatar.jpg" width="w-64" rounded="rounded-full" initials="MS" />
	</div>
	<div class="py-2">
		<h1 class="h1">MAXIMILIEN SCHULLER</h1>
	</div>
	<div class="py-2">
		<p>
			Hey there! I'm Max, a full-stack developer based in Adelaide with experience working with Java
			Spring Boot and React with TypeScript.
		</p>
	</div>
	<div class="flex justify-center">
		<div class="fit-content logo-cloud max-w-full grid-cols-1 justify-center gap-1 lg:!grid-cols-2">
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

<section class="m-6 grid grid-cols-1 justify-items-center">
	<ProjectCard
		url="https://github.com/Eternality5/rmse-want-vs-work"
		title="Predicting Programing Lanuage Adoption"
		content="An investigation into predicting programming language adoption using the results of the StackOverflow
		Developer Survey. This investigation focuses more specifically on if the most loved programming languages
		catagory is a good heuristic for determining future most popular lanuguages. I decided to research this area
		as oftern the languages that are loved the most are generally not the most popular."
		footer="15th June 2023"
	/>
	<ProjectCard
		url="https://github.com/Eternality5/portfolio"
		title="My Portfolio"
		content="This is the website you are looking at right now. I created this website as a way to showcase the projects I
			have worked on and to learn how to use SvelteKit."
		footer="21st August 2024"
	/>
	<ProjectCard
		url="https://github.com/Eternality5/deidentifier"
		title="De-identification Framework"
		content="This is my honours project which I created using Django and HTMX. The application helps users to determine
			what the risks are with releasing their research data to the public."
		footer="31st November 2023"
	/>
</section>
