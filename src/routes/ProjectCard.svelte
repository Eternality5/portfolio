<script lang='ts'>
     export let url: string;
	 export let imgSrc: string;
	 export let imgAlt: string;
	 export let title: string;
	 export let content: string;
	 export let footer: string;
</script>

<a href={url} class="card">
	<img class="p-0 rounded-t-lg aspect-video object-cover" src={imgSrc} alt={imgAlt} />
	<section class="p-3">
		<b>{title}</b> <br/>
		{content}
	</section>
	<footer class="flex-end card-footer"><i>{footer}</i></footer>
</a>