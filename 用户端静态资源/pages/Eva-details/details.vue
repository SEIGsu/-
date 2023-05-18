
<style scoped>
.itemize view{
	background-color: #fdf4f6;
	padding: 13rpx 0;
	text-align: center;
	font-size: 26rpx;
	width: calc(33.3% - 10rpx*2);
	margin: 10rpx;
	border-radius: 10rpx;
}
.itemize{
	display: flex;
	flex-wrap: wrap;
	margin: 10rpx;
	padding-bottom: 20rpx;
	border-bottom: 1px solid #e3e3e4;
}
/* 用户评价 */
.eva-content{
	margin: 40rpx 20rpx;
}
.eva-name{
	display: flex;
	align-items: center;
	height: 80rpx;
}
.eva-name image{
	width: 70rpx;
	height: 70rpx;
	border-radius: 50%;
}
.eva-name text{
	display: block;
}
.eva-com{
	flex: 1;
	padding: 0 10rpx;
	height: 70rpx;
}
.eva-com text:nth-child(2){
	font-size: 26rpx;
	color: #8a8b90;
}
.eva-time{
	align-self: flex-start;
	color: #8a8b90;
	font-size: 26rpx;
}
/* 评论内容 */
.eva-text{
	line-height: 1.3;
	margin: 20rpx 0;
}
.eva-image{
	display: flex;
	flex-wrap: wrap;
}
.eva-image image{
	width: 100%;
	height: 200rpx;
	border-radius: 5rpx;
	display: block;
}
.eva-image view{
	width: calc(33.3% - 5rpx*2);
	margin: 5rpx;
}
</style>