
<style scoped>
.chacha{
	height: 30rpx;
	display: flex;
	justify-content: flex-end;
}
.chacha image{width: 30rpx; height: 30rpx;}
.scroll-hi{height: 1000rpx;}
/* 评论内容 */
.messages-views{
	margin: 20rpx 0;
}
.messages-name image{
	width: 60rpx; height: 60rpx;
	border-radius: 50%;
}
.messages-name{
	display: flex;
	align-items: center;
	height: 60rpx;
}
.nickname{
	flex: 1;
	color: #8a8b90;
	font-size: 30rpx;
	padding-left: 15rpx;
}
.times{
	color: #b0afb4;
	font-size: 25rpx;
}
.messages-title{
	font-size: 30rpx;
	padding-left: 75rpx;
	line-height: 1.4;
	margin: 20rpx 0;
}
/* 固定底部的评论框 */
.Comment-box{
	background-color: #f7f7f7;
	position: fixed;
	bottom: 0;
	right: 0;
	left: 0;
	padding: 10rpx;
	display: flex;
	align-items: center;
	font-size: 27rpx;
	z-index: 99;
	padding-bottom: 68rpx;
}
.Comment-box-input{
	background-color: #FFFFFF;
	border-radius: 10rpx;
	height: 80rpx;
	flex: 1;
}
.Comment-box-input input{
	padding: 0 15rpx;
	height: 80rpx;
}
.send-out{
	background-color: #07c160;
	color: #FFFFFF;
	height: 80rpx;
	line-height: 80rpx;
	width: 150rpx;
	text-align: center;
	border-radius: 10rpx;
	margin-left: 10rpx;
}
.detail-page button{
	margin: 70rpx;
	width: 400rpx;
}
.detail-page{
	position:absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
}
</style>