<script>
	import { Avatar } from '@skeletonlabs/skeleton';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section class="content-center grid">
	<Avatar
		src="avatar.jpg"
		width="w-32"
		rounded="rounded-full"
		initials="MS"
	/>
	<h1 class="h1">Maximilien Schuller</h1>
	<p>
		Hey there! I'm Max, a full-stack developer with a penchant for optimizing resource allocation
		and managing technical debt.
	</p>
	<p />
	<ul>
		<li>
			Background: My journey began with a fascination for code, both on the front end and behind the
			scenes. I thrive on building robust applications that seamlessly connect users with
			technology.
		</li>
		<li>
			Technical Debt Whisperer: When technical debt creeps in (and it always does), I'm the one
			wielding the broom. I identify those hidden corners of code that need cleaning and ensure we
			pay back our debts promptly.
		</li>
		<li>
			Collaborator: I thrive in collaborative environments. From brainstorming sessions to code
			reviews, I value teamwork and believe that diverse perspectives lead to better solutions.
		</li>
		<li>
			Beyond the IDE: When I'm not immersed in code, you'll find me playing videos games, working
			out in the gym, listening to audio books, or going to whatever's on in the city .
		</li>
	</ul>
</section>

<section>
	<h2 class="h2 block">My Projects</h2>
	<div class="flex">
		<div class="card variant-filled p-4">
			<header class="card-header">header</header>
			<section class="p-4">content</section>
			<footer class="card-footer">footer</footer>
		</div>

		<div class="card variant-filled p-4">
			<header class="card-header">header</header>
			<section class="p-4">content</section>
			<footer class="card-footer">footer</footer>
		</div>

		<div class="card variant-filled p-4">
			<header class="card-header">header</header>
			<section class="p-4">content</section>
			<footer class="card-footer">footer</footer>
		</div>
	</div>
</section>
