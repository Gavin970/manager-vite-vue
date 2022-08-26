<template>
	<div>{{a}}</div>
	<button @click="change">change</button>
	<el-button type="primary">ssss</el-button>
</template>

<script setup lang="ts">
	let a = ref('dddd')
	console.log(a)
	function change(){
		a.value = "wuhu~"
	}
</script>

<style scoped>

</style>
