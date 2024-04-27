<template>
	<section class="iphone">
		<div class="container iphone__content">
			<div class="iphone__content-item">
				<h2 class="iphone__content-title">iPhone 11 Pro</h2>
				<img src="@/assets/images/iPhone11Pro.png" alt="" />
				<h3 class="iphone__content-price">Starting at $999</h3>
				<div class="iphone__content-btns">
					<button class="iphone__content-btn">VIEW</button>
				</div>
			</div>
			<div class="iphone__content-item">
				<h2 class="iphone__content-title">iPhone 11</h2>
				<img src="@/assets/images/iPhone11.png" alt="" />
				<h3 class="iphone__content-price">Starting at $699</h3>
				<div class="iphone__content-btns">
					<button class="iphone__content-btn">VIEW</button>
				</div>
			</div>
			<div class="iphone__content-item">
				<h2 class="iphone__content-title">iPhone SE</h2>
				<img src="@/assets/images/iPhoveSE.png" alt="" />
				<h3 class="iphone__content-price">Starting at $399</h3>
				<div class="iphone__content-btns">
					<button class="iphone__content-btn">VIEW</button>
				</div>
			</div>
			<div class="iphone__content-item">
				<h2 class="iphone__content-title">iPhone XR</h2>
				<img src="@/assets/images/iPhoneXR.png" alt="" />
				<h3 class="iphone__content-price">Starting at $599</h3>
				<div class="iphone__content-btns">
					<button class="iphone__content-btn">VIEW</button>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {}
</script>

<style>
.iphone__content {
	display: flex;
	align-items: center;
	justify-content: center;
	gap: 30px;
}
.iphone__content-item {
	margin-top: 79px;
	display: flex;
	flex-direction: column;
	align-items: center;
	border-radius: 6px;
	background: #fff;
	padding: 15px 58px;
	max-width: max-content;
}
.iphone__content-title {
	font-family: 'Montserrat';
	color: #000;
	font-size: 20px;
	font-weight: 700;
	margin-bottom: 10px;
}
.iphone__content-price {
	margin-top: 10px;
	color: rgb(0, 0, 0);
	font-family: 'Montserrat';
	font-size: 14px;
	font-weight: 400;
	line-height: 17px;
	text-transform: uppercase;
}
.iphone__content-btns {
	margin-top: 20px;
	display: flex;
}
.iphone__content-btn {
	background: rgb(21, 21, 21);
	color: rgb(255, 255, 255);
	font-family: 'Montserrat';
	font-size: 16px;
	font-weight: 700;
	line-height: 20px;
	text-transform: uppercase;
	padding: 7px 57px;
	transition: 1s;
}
.iphone__content-btn:hover {
	background: rgb(4, 0, 255);
	transform: scale(1.1) translateY(-5px);
}
</style>
