<template>
	<footer class="footer">
		<div class="container footer__content">
			<a href="#" class="footer__logo">
				<img src="@/assets/images/logo.svg" alt="" />
			</a>
			<ul class="footer__list">
				<li v-for="(link, i) in links" :key="i">
					<a href="" class="footer__list-link">
						{{ link.name }}
					</a>
				</li>
			</ul>
            <div class="footer__content-payment">
                <a href="#"><img src="@/assets/images/Visa.png" alt=""></a>
                <a href="#"><img src="@/assets/images/mastercard.png" alt=""></a>
            </div>
		</div>
	</footer>
</template>

<script>
export default {
	data() {
		return {
			links: [
				{ name: 'iMac', to: 'iMac' },
				{ name: 'iPad', to: 'iPad' },
				{ name: 'iPhone', to: 'iPhone' },
			],
		}
	},
}
</script>

<style>
.footer {
	margin-top: 55px;
	padding: 81px 0;
	box-shadow: 0px -4px 20px 0px rgba(0, 0, 0, 0.25);
	background: rgb(40, 40, 40);
}
.footer__content {
	display: flex;
	align-items: center;
	justify-content: space-between;
}

.footer__list {
	display: flex;
	gap: 30px;
}
.footer__list-link {
	font-family: 'Montserrat';
	color: rgb(255, 255, 255);
	font-size: 20px;
	font-weight: 700;
	line-height: 24px;
	letter-spacing: 0%;
}
.footer__content-payment {
    display: flex;
    gap: 29px;
}
</style>
