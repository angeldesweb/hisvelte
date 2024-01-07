<script>
	import { Menu } from '$lib/icons';
</script>

<div class="dropdown">
	<div tabindex="-1" role="button" class="btn btn-ghost lg:hidden">
		<Menu />
	</div>
	<ul
		tabindex="-1"
		class="menu dropdown-content menu-sm z-[1] mt-3 w-52 rounded-box bg-base-100 p-2 shadow"
	>
		<li><a href={null}>Item 1</a></li>
		<li>
			<a href={null}>Parent</a>
			<ul class="p-2">
				<li><a href={null}>Submenu 1</a></li>
				<li><a href={null}>Submenu 2</a></li>
			</ul>
		</li>
		<li><a href={null}>Item 3</a></li>
	</ul>
</div>
