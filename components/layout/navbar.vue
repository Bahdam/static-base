<template>
	<nav>
		<NuxtLink to="/">Home</NuxtLink>
		<NuxtLink to="/test-1">Test 1</NuxtLink>
		<NuxtLink to="/test-2">Test 2</NuxtLink>
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