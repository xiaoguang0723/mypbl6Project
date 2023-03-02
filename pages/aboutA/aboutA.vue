<template>
	<view class="wrap">
		<view class="top">
			<image src="../../static/avatar.jpg" mode=""></image>
		</view>
		<view class="txt">
			基于玩安卓api与uniapp开发安卓平台玩安卓客户端
		</view>
		<view class="connect">
			<view>
				QQ:1161946586
			</view>
			<view>
				邮箱：1161946586@qq.com
			</view>
			<view>
				
			</view>
		</view>
		<view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>
	.wrap{
		height: 100vh;
		background: #efefef;
		display: flex;
		flex-direction: column;
		justify-content: space-around;
		align-items: center;
		padding-bottom: 50px;
		color: #333;
	}
	.txt{
		padding: 0 25px;
		text-align: center;
		font-size: 48rpx;
	}
.top{
	width: 100px;
	height: 100px;
	border-radius: 50%;
	overflow: hidden;
	margin: 0 auto;
	margin-top: 50px;
}
.top image{
	width: 100%;
	height: 100%;
}
</style>
