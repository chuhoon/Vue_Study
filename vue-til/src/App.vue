<template>
	<div id="app">
		<img alt="Vue logo" src="./assets/logo.png" />
		<HelloWorld msg="Welcome to Your Vue.js App" />
	</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import AppHeader from './components/common/AppHeader.vue';

export default {
	name: 'App',
	components: {
		HelloWorld,
		AppHeader,
	},
	//
	created() {
		console.log('안녕');
		console.log('안녕2');
	},
};
</script>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>
