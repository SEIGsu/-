
<style scoped>
.search-mar{
	margin: 0 20rpx;
	display: flex;
	align-items: center;
}
.search-mar view:nth-child(2){
	height: 70rpx;
	line-height: 70rpx;
	padding-left: 30rpx;
}
.search-input{
	display: flex;
	flex-direction: row;
	flex: 1;
	position: relative;
}
.search-input image{
	width: 35rpx;
	height: 35rpx;
	position: absolute;
	left: 20rpx;
	align-self: center;
}
.search-input input{
	background-color: #f4f4f4;
	width: 100%;
	height: 70rpx;
	padding: 0 20rpx 0 75rpx;
	border-radius: 8rpx;
}
/* 历史记录 */
.history image{
	display: block;
	width: 30rpx;
	height: 30rpx;
}
.history{
	display: flex;
	align-items: center;
	justify-content: space-between;
	margin: 40rpx 20rpx;
	font-size: 30rpx;
	font-weight: bold;
}
.history-text{
	display: flex;
	flex-wrap: wrap;
	margin: 0 20rpx;
}
.history-text text{
	background-color: #f4f4f4;
	margin: 0 20rpx 20rpx 0;
	border-radius: 7rpx;
	padding: 10rpx 20rpx;
	font-size: 28rpx;
}

</style>