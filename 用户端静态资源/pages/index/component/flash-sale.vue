
<style scoped>
.flash-view{
	background: linear-gradient(to bottom, #ed7d79 25%, #fceeed 70%);
	border-radius: 20rpx;
	padding: 20rpx 0;
	margin: 30rpx 20rpx 0 20rpx;
}
.count-down{
	color: #FFFFFF;
	padding-bottom: 15rpx;
	padding-left: 20rpx;
	font-style: oblique;
	font-weight: bold;
}
/* 宫格布局 */
.flex-view{
	display: flex;
	flex-wrap: wrap;
	margin: 0 20rpx;
}
.commodity{
	width: calc(25% - 10rpx*2);
	margin: 10rpx;
}
.commodity image{
	width: 100%;
	height: 150rpx;
	border-radius: 20rpx;
}
.commodity view{
	width: 90%;
}
.commodity view text:nth-child(1){
	margin: 10rpx 0;
}
.commodity view text:nth-child(2){
	color: #999999;
	font-weight: bold;
}
.commodity view text:nth-child(3){
	text-decoration: line-through;
	font-size: 25rpx;
	color: #bfbfbf;
	padding-left: 10rpx;
}
.overflow{
	-webkit-line-clamp: 1 !important;
}
</style>