<script setup lang="ts">
const brand = useBrand();
</script>
<template>
	<div>
		<footer>
			<a>Shop</a>
			<a>Privacy Policy</a>
			<a>© {{ brand.brandName }} 2023</a>
		</footer>
	</div>
</template>
<style>
footer {
	width: 100%;
	display: flex;
	justify-content: space-between;
}
footer > a {
	padding: 5px;
}
</style>