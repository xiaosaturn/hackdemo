<template>
	<view class="content">
		<view class="person-profile">
			<image class="logo" src="/static//avatar.png"></image>
			<view class="nickname">
				<text class="title">{{ title }}</text>
				<view class="qm">该用户没有签名</view>
			</view>
		</view>
		<view class="article">
			小知不及大知，小年不及大年。奚以知其然也？朝菌不知晦朔，蟪蛄不知春秋，此小年也。楚之南有冥灵者，以五百岁为春，五百岁为秋；
			上古有大椿者，以八千岁为春，八千岁为秋，此大年也。而彭祖乃今以久特闻，众人匹之，不亦悲乎！
		</view>
		<view class="image-con">
			<image class="img" src="../../static/11.png"></image>
			<image class="img" src="../../static/22.png"></image>
			<image class="img" src="../../static/33.png"></image>
		</view>
		<view class="time">03-20 09:11</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: '超短裙男孩儿'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style lang="scss" scoped>
	.content {
		padding: 20rpx;
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		justify-content: flex-start;
		
		.person-profile {
			display: flex;
			margin-bottom: 16rpx;
		}
		.logo {
			width: 88rpx;
			height: 88rpx;
			border-radius: 44rpx;
			margin-right: 40rpx;
		}
		.nickname {
			
		}
		.title {
			font-weight: 500;
			font-size: 28rpx;
			color: #3d3d3d;
			line-height: 44rpx;
			margin-bottom: 12rpx;
		}
		.qm {
			line-height: 32rpx;
			font-size: 24rpx;
			color: #3d3d3d;
		}
		.article {
			font-size: 28rpx;
			line-height: 44rpx;
			color: #3d3d3d;
			margin-bottom: 30rpx;
			font-weight: 300;
		}
		.image-con {
			display: flex;
			justify-content: space-evenly;
			width: 100%;
		}
		.img {
			width: 200rpx;
			height: 200rpx;
			border-radius: 8rpx;
			margin-bottom: 20rpx;
		}
		.time {
			font-weight: 300;
			font-size: 28rpx;
			line-height: 44rpx;
		}
	}
</style>
