<template>
	<view>
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		// 监听原生标题导航按钮点击事件
		onNavigationBarButtonTap(e) {
			if (e.index == 0) {
				uni.navigateBack({
					delta: 1
				});
			}
		},
		// 监听搜索框文本变化
		onNavigationBarSearchInputChanged() {
			console.log('监听搜索框文本变化');
		},
		// 监听点击手机上的输入法中的搜索按钮事件
		onNavigationBarSearchInputConfirmed() {
			console.log('搜索按钮事件');
		},
		methods: {
			
		}
	}
</script>

<style>

</style>
