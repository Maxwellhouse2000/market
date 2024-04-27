<template>
	<div class="wrapper">
		<header class="header">
			<NavBar />
			<HeaderContent />
		</header>
		<MainSection />
		<SectionTwo />
		<SectionThree />
		<SectionApple />
		<Footer />
	</div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import HeaderContent from './components/HeaderContent.vue'
import MainSection from './components/MainSection.vue'
import SectionTwo from './components/SectionTwo.vue'
import SectionThree from './components/SectionThree.vue'
import SectionApple from './components/SectionApple.vue'
import Footer from './components/Footer.vue'

export default {
	components: {
		NavBar,
		HeaderContent,
		MainSection,
		SectionTwo,
		SectionThree,
		SectionApple,
		Footer,
	},
}
</script>

<style>
* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}
a {
	text-decoration: none;
}
li {
	list-style: none;
}
input,
button {
	background: none;
	outline: none;
	border: none;
	transition: 0.5s;
}

.container {
	width: 100%;
	max-width: 1140px;
	padding: 0 15px;
	margin: 0 auto;
}
</style>
