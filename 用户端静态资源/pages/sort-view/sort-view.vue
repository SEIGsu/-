
<style scoped>
.sort-view{
	display: flex;
}
.sort-left{
	width: 200rpx;
	text-align: center;
	background-color: #f6f6f6;
	height: 100vh;
	position: fixed;
	left: 0;
	top: 0;
	bottom: 0;
}

.sort-left text{
	display: block;
	color: #5f5f5f;
	padding: 20rpx 0;
	border-bottom: 1px solid #FFFFFF;
	font-size: 28rpx;
}
/* 左边选中*/
.Select-style{
	background-color: #FFFFFF !important;
}
/* 右边 */
.sort-right{
	margin: 0 20rpx 0 220rpx;
	flex: 1;
}
.Title{
	padding: 20rpx 0;
	font-size: 28rpx;
	font-weight: bold;
}
.Commodity{
	display: flex;
	height: 150rpx;
	margin-bottom: 20rpx;
}
.Com-image{
	width: 150rpx;
	height: 150rpx;
}
.Commodity image{
	width: 150rpx;
	height: 150rpx;
	border-radius: 10rpx;
}
.Com-price{
	flex: 1;
	position: relative;
	padding-left: 20rpx;
	font-weight: bold;
}
.Com-price text:nth-child(2){
	position: absolute;
	bottom: 0;
	color: #f36825;
}
</style>