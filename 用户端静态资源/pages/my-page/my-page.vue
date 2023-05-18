
<style scoped>
.my-page{
	height: 300rpx;
	/* background: #4CD964; */
	background: linear-gradient(to bottom, #e94b37 25%, #e59f95 100%);
	position: relative;
	padding-top: 100rpx;
}
.my-name image{
	display: block;
	width: 100rpx;
	height: 100rpx;
	border-radius: 50%;
	margin-bottom: 10rpx;
}
.my-name{
	color: #FFFFFF;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	height: 230rpx;
	font-size: 33rpx;
	z-index: 9;
	position: absolute;
	left: 0;
	right: 0;
}
.shuibo-img{
	position: absolute;
	bottom: 0;
	left: 0;
	width: 100%;
	height: 170rpx;
	/* z-index: 99; */
	mix-blend-mode: screen;
}
/* 我的订单 */
.my-order{
	margin-top: 20rpx;
	padding: 0 20rpx;
}
.my-order-title image{
	width: 30rpx;
	height: 30rpx;
	display: block;
	margin-left: 10rpx;
}
.my-order-title{
	display: flex;
	justify-content: space-between;
}
.my-order-title view:nth-child(1){
	font-weight: bold;
}
.my-order-title view:nth-child(2){
	font-size: 25rpx;
	color: #cfcfcf;
}
.more{
	display: flex;
	align-items: center;
}
.order-state image{
	display: block;
	width: 50rpx;
	height: 50rpx;
	margin-bottom: 10rpx;
}
.order-state{
	display: flex;
	align-items: center;
	justify-content: space-between;
	margin-top: 30rpx;
}
.order-state view{
	display: flex;
	align-items: center;
	flex-direction: column;
	color: #4f4f4f;
}
/* 其他功能 */
.my-other{
	background-color: #FFFFFF;
	margin: 50rpx 20rpx 20rpx 20rpx;
	box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
	border-radius: 6rpx;
	padding: 0 10rpx;
	color: #828282;
}
.my-other image{
	display: block;
	width: 35rpx;
	height: 35rpx;
	margin-right: 20rpx;
}
.my-other view{
	display: flex;
	align-items: center;
	padding: 30rpx 0;
}
.my-other view:nth-child(2){
	border-bottom: 1rpx solid #e0e0e0;
	border-top: 1rpx solid #e0e0e0;
}
.my-other text{
	flex: 1;
}
.my-other-deta{
	width: 30rpx !important;
	height: 30rpx !important;
	margin: 0 !important;
}
</style>