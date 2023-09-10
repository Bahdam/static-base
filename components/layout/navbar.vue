<template>
	<nav>
		<NuxtLink to="/">Home</NuxtLink>
		<NuxtLink to="/">Test 1</NuxtLink>
		<NuxtLink to="/">Test 2</NuxtLink>
	</nav>
</template>
<style>
nav > a {
	padding: 5px;
	color: var(--col-secondary);
	justify-content: space-between;
}
nav {
	display: flex;
	padding: 20px;
	background-color: var(--col-primary);
	position: fixed;
	width: 100vw;
	top: 0;
}
</style>