
<style scoped>
.video-return{
	position: fixed;
	top: 0;
	left: 0;
	right: 0;
	z-index: 99;
}
.video-return-img view{
	width: 50rpx;
	display: flex;
	align-items: center;
	padding-left: 20rpx;
}
.video-return-img image{
	width: 50rpx;
	height: 50rpx;
	display: block;
}
/* 视频 */
.trim-video{
	width: 100%;
	position: relative;
	overflow: hidden;
}
.trim-video video{
	width: 100%;
}
/* 透明覆盖 */
.all-round{
	position: fixed;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	background-color: rgba(0,0,0,0.01);
}
/* 自定义按钮 */
.video-img image{
	width: 110rpx;
	height: 110rpx;
	z-index: 999;
	/* border: 2px solid #FFFFFF;
	border-radius: 50%; */
}
.video-img{
	width: 110rpx;
	height: 110rpx;
	position: absolute;
	bottom: 0;
	left: 50%;
	top: 50%;
	transform: translateX(-50%) translateY(-50%);
}
/* 详情页和标题 */
.advert-left{
	position: absolute;
	left: 20rpx;
	bottom: 85rpx;
}
.goods-det{
	/* height: 170rpx; */
	width: 300rpx;
	background-color: red;
	border-radius: 10rpx;
	margin-bottom: 20rpx;
}
.goods-det image{
	height: 120rpx;
	width: 300rpx;
	display: block;
	border-top-left-radius: 10rpx;
	border-top-right-radius: 10rpx;
}
.goods-price text{display: block;}
.goods-price{
	display: flex;
	/* align-items: center; */
	justify-content: space-between;
	padding: 9rpx 10rpx;
	font-size: 27rpx;
	color: #FFFFFF;
	font-weight: bold;
}
.goods-title{
	width: 500rpx;
	line-height: 1.5;
	font-size: 30rpx;
	color: #FFFFFF;
}
/* 右边用户操作 */
.user-right{
	position: absolute;
	right: 20rpx;
	bottom: 85rpx;
	width: 100rpx;
	font-size: 25rpx;
	color: #FFFFFF;
}
.user-right image{
	width: 55rpx;
	height: 55rpx !important;
}
.give-thethu{
	display: flex;
	flex-direction: column;
	align-items: center;
}
.give-thethu button{
	border: navajowhite;
	padding: inherit !important;
	margin: 0 !important;
	font-size: 25rpx !important;
	line-height: inherit !important;
	color: #FFFFFF !important;
}
.comment{margin: 60rpx 0;}
</style>