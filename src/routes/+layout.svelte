<script>
	import '../app.pcss';
	import Header from './Header.svelte';
	import './styles.css';
	import { AppShell } from '@skeletonlabs/skeleton';
</script>

<div class="app">
	<AppShell>
		<Header slot="header"></Header>
		<slot />
	</AppShell>
</div>
