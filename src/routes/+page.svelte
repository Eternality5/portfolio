<script>
	import {Avatar} from "@skeletonlabs/skeleton"
	import ProjectCard from "./ProjectCard.svelte";
</script>

<svelte:head>
	<title>Home</title>
	<meta name="Home Page" content="Portfolio website for Maximilien Schuller" />
</svelte:head>

<section class="text-middle p-20 text-center">
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

<section class="p-20">
	<h1 class="h1">My Projects</h1>
	<div class="grid grid-cols-1 lg:!grid-cols-3 content-start gap-4">
		<ProjectCard 
			url="https://github.com/Eternality5/portfolio" 
			title="My Portfolio"
			imgSrc="cardheaders/portfolio.png" 
			imgAlt="me"
			content="This is the website you are looking at right now. I created this website as a way to showcase the projects I
			have worked on and to learn how to use SvelteKit." 
			footer="By Maximilien Schuller" />
		<ProjectCard 
			url="https://github.com/Eternality5/g1-serp2023" 
			title="De-identification Framework"
			imgSrc="avatar.jpg" 
			imgAlt="me"
			content="This is my honours project which I created using Django and HTMX. The application helps users to determine
			what the risks are with releasing their research data to the public." 
			footer="By Maximilien Schuller, Vinay Kumar & SA Health" />
		<ProjectCard 
			url="https://github.com/Eternality5/portfolio" 
			title="Predicting Popularity of Programming Languages"
			imgSrc="avatar.jpg" 
			imgAlt="Graph"
			content="A research paper I wrote where I analyse the Stack Overflow developer survey to determine if it can be used to
			predict trends in the popularity of programming languages." 
			footer="By Maximilien Schuller" />
	</div>
	
</section>
