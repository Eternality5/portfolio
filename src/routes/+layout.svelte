<script>
	import { AppShell } from '@skeletonlabs/skeleton';
import '../app.pcss';
	import Header from './Header.svelte';
</script>

<AppShell slotSidebarLeft>
	<Header slot="header" />
	<div class="">
		<slot />
	</div>

</AppShell>
