<template>
	<view class="content">
		<image class="main" src="/static/main.jpg"></image>
		<view class="login-module">
			<navigator url="../Login/user/user" hover-class="navigator-hover">
				<button type="primary">应聘者登录</button>
			</navigator>
		</view>
		<view class="login-module">
			<navigator url="../Login/user/zhaopinzhe/zhaopinzhe" hover-class="navigator-hover">
				<button type="primary">招聘者登录</button>
			</navigator>
		</view>
	</view>
</template>

<script>
	
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		text-align: center;
	}

	.logo {
		height: 200upx;
		width: 200upx;
		margin-top: 250upx;
	}

	.login-module {
		margin-left: 50upx;
		margin-right: 50upx;
		margin-top: 50upx;
		margin-bottom: 30upx;
	}
</style>
