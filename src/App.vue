<script setup>
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
	<div>
		<h1>HEJ GRUPPEN</h1>
		<h2>Hej Peter</h2>
		<h3>Hej Linda</h3>
		<p>Peter Ändrar för att testa</p>
		<p>Hej patrik</p>
		<p>Hej patrik2</p>
	</div>
	<div>
		<ul>
			<li>
				varmkorv
			</li>
			<li>
				falukorv
			</li>
			<li>
				ölkorv
			</li>
			<li>
				tokkorv
			</li>
			<li>
				lökkorv
			</li>
		</ul>

	</div>
	<HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
	height: 6em;
	padding: 1.5em;
	will-change: filter;
	transition: filter 300ms;
}
.logo:hover {
	filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
	filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
