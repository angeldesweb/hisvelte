<script>
	import { DesktopMenu, MobileMenu } from './Menus';
</script>

<header class="navbar bg-base-200">
	<div class="navbar-start">
		<MobileMenu />
		<a href="/" class="btn btn-ghost text-xl">hisvelte</a>
	</div>
	<div class="navbar-center hidden lg:flex">
		<DesktopMenu />
	</div>
	<div class="navbar-end">
		<a href={null} class="btn">Button</a>
	</div>
</header>
