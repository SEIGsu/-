
<style scoped>
.login-view{
	position: fixed;
	top:0;
	right: 0;
	left: 0;
	bottom: 0;
	background-color: #FFFFFF;
	z-index: 999;
	animation: post-list-row .3s;
}
@keyframes post-list-row {
	0% {top:100%}
	100%{top:0}
}

.login-button{
	position:absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
}
.login-view button{
	margin: 70rpx;
	width: 400rpx;
}
</style>