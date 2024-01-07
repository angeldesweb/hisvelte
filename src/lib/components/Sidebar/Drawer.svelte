<script>
	import { Navbar } from '$lib/components';
	import { SidebarExpand } from '$lib/icons';
	import SidebarMenu from './SidebarMenu.svelte';

	let { children } = $props();
</script>

<div class="drawer lg:drawer-open">
	<input id="my-drawer-2" type="checkbox" class="drawer-toggle" />
	<div class="drawer-content">
		<label for="my-drawer-2" class="btn btn-square btn-ghost drawer-button lg:hidden">
			<SidebarExpand />
		</label>
		{@render children()}
	</div>
	<div class="drawer-side">
		<label for="my-drawer-2" aria-label="close sidebar" class="drawer-overlay"></label>
		<ul
			class="menu min-h-full w-24 bg-base-200 p-4 text-base-content text-transparent hover:w-72 hover:text-primary"
		>
			<!-- Sidebar content here -->
			<SidebarMenu />
		</ul>
	</div>
</div>
