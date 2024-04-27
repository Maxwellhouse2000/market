<template>
    <nav class="nav">
        <div class="container nav__content">
            <a href="#" class="nav__logo">
				<img src="@/assets/images/logo.svg" alt="" />
			</a>
			<ul class="nav__list">
				<li v-for="(link, i) in links" :key="i">
					<a href="" class="nav__list-link">
						{{ link.name }}
					</a>
				</li>
			</ul>
        </div>
    </nav>
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
.nav {
	padding: 6px 0;
	box-shadow: 0px 4px 20px 0px rgba(0, 0, 0, 0.25);
	background: rgb(40, 40, 40);
}

.nav__content {
	display: flex;
	gap: 30px;
	align-items: center;
}

.nav__list {
	display: flex;
	gap: 30px;
}
.nav__list-link {
	font-family: 'Montserrat';
	color: rgb(255, 255, 255);
	font-size: 20px;
	font-weight: 700;
	line-height: 24px;
	letter-spacing: 0%;
}

</style>
