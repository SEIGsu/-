
<style scoped>
/* 轮播区域 */
.Rotation-view {
	height: 320rpx;
	/* background: linear-gradient(to bottom, #4CD964 25%, #c0f2c8 100%); */
	background: linear-gradient(to bottom, #e94b37 25%, #e59f95 100%);
	padding: 20rpx 20rpx 0 20rpx;
}

.swiper-top {
	height: 300rpx;
	position: relative;
}

.swiper {
	height: 300rpx !important;
	border-radius: 20rpx;
	overflow: hidden;
	transform: translateY(0);
}

.swiper-item image {
	width: 100%;
	height: 300rpx !important;
}

/* 指示点 */
.instruct-view {
	display: flex;
	justify-content: center;
	position: absolute;
	bottom: 10rpx;
	left: 0;
	width: 100%;
}

.instruct {
	background: #4e90a6;
	height: 10rpx;
	width: 30rpx;
	border-radius: 50rpx;
	margin: 0 10rpx;
}

.active {
	background: #FFFFFF !important;
}
</style>