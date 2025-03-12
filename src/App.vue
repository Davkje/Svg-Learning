<script setup>
import HomeComp from "./components/HomeComp.vue";
</script>

<template>
	<img class="bgimg" src="/src/assets/map1.webp" alt="Background image of a map">
	<div class="filter"></div>
	<div class="wrapper">
		<HomeComp />
	</div>
</template>

<style lang="scss" scoped>
.filter {
	position: absolute;
	background-color: #040420f6;
	width: 100vw;
	height: 100vh;
	mix-blend-mode: multiply;
	z-index: 1;
}

.wrapper {
	position: fixed;
	top: 0;
	left: 0;
	width: 100vw;
	height: 100vh;
	display: flex;
	justify-content: center;
	align-items: center;
  z-index: 10;
}
</style>
