<script lang="ts">
	export let url: string;
	export let imgSrc: string = "";
	export let imgAlt: string = "";
	export let title: string;
	export let content: string;
	export let footer: string;
</script>

<a href={url} class="card mb-6">
	<div class="strong min-w-full max-w-5xl">
		{#if imgSrc !== ""}
			<img class="object-contain max-h-96 aspect-video rounded-t-lg p-0" src={imgSrc} alt={imgAlt} />
		{/if}
		<section class="p-3">
			<h3 class="bold h3">{title}</h3>
			{content}
		</section>
		<footer class="flex-end card-footer">
			<i>{footer}</i>
		</footer>
	</div>
</a>
