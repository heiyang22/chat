<template>
	<view class="container">
		我是首页
		<button @click="onClick">点点试试</button>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				href: 'https://uniapp.dcloud.io/component/README?id=uniui'
			}
		},
		methods: {
			onClick(){
				console.log(this);
				this.$uni.navigateTo({
				
				  url: '/pages/home/home'
				
				})
			}

		}
	}
</script>

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>
