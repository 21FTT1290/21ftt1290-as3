<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
	<div class="flex flex-col justify-center max-w-xs p-6 shadow-md rounded-xl sm:px-12 dark:bg-gray-900 dark:text-gray-100">
		<img src="src/assets/shmi.jpg" alt="" class="w-32 h-32 mx-auto rounded-full dark:bg-gray-500 aspect-square">
		<div class="space-y-4 text-center divide-y divide-gray-700">
			<div class="my-2 space-y-1">
				<h2 class="text-xl font-semibold sm:text-2xl">Shahmi Haqeemi </h2>
				<p class="px-5 text-xs sm:text-base dark:text-gray-400">Politeknik Brunei Student <br> 21FTT1290</p>
			</div>
		</div>
	</div>
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
