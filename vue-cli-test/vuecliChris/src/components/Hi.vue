<template>
	<div>
		<h2>{{ msg }}</h2>
    <router-view class="aaa"></router-view>
	</div>
</template>

<script>
	export default {
		name: 'hi',
		data() {
			return {
				msg: 'hi page'
			}
		}
	}
</script>

<style scoped>

</style>
