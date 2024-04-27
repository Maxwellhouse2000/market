<template>
	<main class="main">
		<section class="airpods">
			<div class="container airpods__content">
				<p class="airpods__descr">
					We refined the details of comfort, creating a new class of in-ear
					headphones with a customizable fit that forms an exceptional seal for
					Active Noise Cancellation. You’ll feel your music, not your
					headphones.
				</p>
				<img src="@/assets/images/airpods.png" alt="" />
			</div>
		</section>
	</main>
</template>

<script>
export default {

}
</script>

<style>
.main {
	margin-top: 130px;
}


.airpods__content {
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.airpods__descr {
    max-width: 538px;
	color: rgb(255, 255, 255);
	font-family: 'Montserrat';
	font-size: 22px;
	font-weight: 500;
	line-height: 27px;
	letter-spacing: 0%;
}
</style>
