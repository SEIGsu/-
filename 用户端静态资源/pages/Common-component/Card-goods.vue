
<style scoped>
.card-view{
	display: flex;
	flex-wrap: wrap;
	margin: 20rpx 10rpx;
}
.Card-stream{
	width: calc(50% - 10rpx*2);
	margin: 10rpx;
	background: #FFFFFF;
	border-radius: 10rpx;
}
.Card-image{
	height: 400rpx;
}
.Card-stream image{
	width: 100%; 
	height: 400rpx;
	border-top-left-radius: 10rpx;
	border-top-right-radius: 10rpx;
}
.Card-title{
	font-size: 28rpx;
	height: 80rpx;
	line-height: 40rpx;
	margin: 10rpx 15rpx;
}
.Card-price{
	display: flex;
	align-items: center;
	justify-content: space-between;
	padding: 0 15rpx 15rpx 15rpx;
}
.Card-price text:nth-child(1){
	color: #e9445a;
	font-weight: bold;
}
.Card-price text:nth-child(2){
	color: #b0b1b4;
	font-size: 25rpx;
}
</style>