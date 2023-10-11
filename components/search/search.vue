<template>
	<view>
		<!-- 搜索框 -->
		<button>333</button>
		<button>222</button>
		<button class="1324"></button>
		<view class="search" @click="toSearch">
			<text class="cuIcon cuIcon-search icon-search"></text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			};
		},
		methods:{
			/**
			 * 跳转到搜索页面
			 * @param {}
			 */
			toSearch() {
				uni.navigateTo({
					url: '/pages/index/search/search'
				})
			}
		}
	}
</script>

<style lang="scss">
.search {
	background-color: #EDEFF2;
    border-radius: 20px;
    width: 650rpx;
    margin: 20rpx auto;
    padding: 10rpx;
	
	.icon-search {
		color: #2771B1;
		font-weight: bold;
		font-size: 50rpx;
		margin-left: 20rpx;
	}
}
</style>
