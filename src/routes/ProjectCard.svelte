<script lang="ts">
	export let url: string;
	export let imgSrc: string;
	export let imgAlt: string;
	export let title: string;
	export let content: string;
	export let footer: string;
</script>

<a href={url} class="card max-w-5xl min-w-5xl">
	<img class="aspect-video rounded-t-lg object-cover p-0" src={imgSrc} alt={imgAlt} />
	<section class="p-3">
		<b>{title}</b> <br />
		{content}
	</section>
	<footer class="flex-end card-footer">
		<i>{footer}</i>
	</footer>
</a>
