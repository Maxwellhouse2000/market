<template>
	<div class="header__content">
		<h1 class="header__title">AirPods Pro</h1>
		<div class="header__btn">
			<a href="" class="header__btn-link"
				>official site <img src="@/assets/icons/Vector.png" alt=""
			/></a>
		</div>
	</div>
</template>

<script>
export default {}
</script>

<style>
.header__content {
	min-height: 635px;
	background-image: url('@/assets/images/Header.png');
	background-position: center;
	background-repeat: no-repeat;
	background-size: cover;
	display: flex;
	align-items: center;
	justify-content: center;
	flex-direction: column;
}
.header__title {
	color: rgb(255, 255, 255);
	font-family: 'ProstoOne';
	font-size: 100px;
	font-weight: 400;
	line-height: 75px;
	letter-spacing: 0%;
}
.header__btn {
	margin-top: 51px;
	display: flex;
	gap: 11px;
}

.header__btn-link {
	border-radius: 10px;
	background: rgb(255, 255, 255);
	color: rgb(23, 23, 24);
	font-family: 'Montserrat';
	font-size: 20px;
	font-weight: 500;
	line-height: 24px;
	letter-spacing: 0%;
	padding: 13px 14px;
	text-transform: uppercase;
	transition: 1s;
}
.header__btn-link:hover {
	background: rgb(212, 255, 0);
	transform: scale(1.1) translateY(-5px);
}
</style>
