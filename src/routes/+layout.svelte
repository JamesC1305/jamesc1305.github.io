<script>
	import '../app.css';
	import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
</script>

<Navbar rounded color="form">
	<NavBrand href="/">
		<span class="self-center whitespace-nowrap text-3xl font-bold dark:text-white">JC</span>
	</NavBrand>
	<NavHamburger />
	<NavUl>
		<NavLi href="/" active={true}>Home</NavLi>
		<NavLi href="/about">About</NavLi>
		<NavLi href="/blog">Blog</NavLi>
	</NavUl>
</Navbar>
<slot></slot>
