<template>
	<view class="u-padding-20">
		<view class="shadow-md u-flex u-row-around u-p-l-30 border-lg">
			
			<view>
				<u-avatar :src="src" size="200"></u-avatar>
			</view>
			<view class="u-padding-40">
				<view class="u-flex-col">
					<text class="font-main font-lg u-m-b-6">Tdx Strategy</text>
					<text class="font-tips font-sm u-m-b-14">huang - dong</text>
					<text class="font-content font-base">sdfa asdfas dfa sdf asdfa sdfasdf asdf asdfa dsfasdfa sdfasdf asdf asdfads fadsf</text>
				</view>
				
				<view class="u-flex u-m-t-24">
					<view class="btn-icon u-flex-col u-row-center u-col-center">
						<text class="count">20</text>
						<u-icon name="thumb-up icon" size="25rpx"></u-icon>
						
						
					</view>
					
					<view class="btn-icon u-flex-col u-row-center u-col-center u-m-l-40">
						<text class="count">20</text>
						<u-icon name="chat icon" size="25rpx"></u-icon>
						
						
					</view>
					
					<view class="btn-icon u-flex-col u-row-center u-col-center u-m-l-40">
						<text class="count">20</text>
						<u-icon name="pushpin icon" size="25rpx"></u-icon>
						
						
					</view>
					
					
				</view>
				
				
			</view>
			
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
				src:"http://pic2.sc.chinaz.com/Files/pic/pic9/202002/hpic2119_s.jpg"
				
			};
		}
	}
</script>

<style lang="scss">
	.btn-icon{
	
		width: 70rpx;
		height: 70rpx;
		border-radius: 35rpx;
		box-shadow: 0 0 2.5px 2.5px rgba(0, 0, 0, 0.06),0 0 5px 5px rgba(0, 0, 0, 0.02);
		.count{
			font-size: 20rpx;
		}
	
	}
		

</style>
