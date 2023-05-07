<template>
	<section class="underheader">
			<div class="underheader__content">
				<div class="underheader__content__item underheader__content__item--text">
					<div class="underheader__content__subtitle">Featured Course</div>
					<div class="underheader__line">
						<div class="default-line"></div>
					</div>
					<div class="underheader__title default-title">
						Run your own online learning platform
					</div>
					<div class="underheader__desc">
						A deep-dive on the Instagram algorythm, hashtags, content strategy, and branding.
					</div>
					<div class="underheader__author">
						<div class="default-author">Kathryn Murphy</div>
					</div>
					<div class="underheader__content__button">
						<a class="default-btn btn-black" href="#">Learn More</a>
					</div>
				</div>
				<div class="underheader__content__item">
					<img src="@/assets/header-img.png" alt="image">
				</div>
			</div>
		</section>
</template>

<script>

</script>

<style scoped>
	.underheader__content {
	background-color: #23233B;
	display: flex;
	justify-content: space-between;

	max-width: 1440px;
	margin: 0 auto;
	padding-left: 82px;
}

.underheader__content__item img {
	padding-top: 104px;
}

.underheader__content__subtitle {
	padding-top: 144px;
	text-transform: uppercase;
	font-size: 16px;
	letter-spacing: 1px;
	line-height: 20.8px;
	margin-bottom: 7px;
}

.underheader__line {
	margin-bottom: 60px;
}

.underheader__title {
	font-size: 55px;
	line-height: 60.5px;
	margin-bottom: 22px;
	max-width: 510px;
}

.underheader__desc {
	max-width: 548px;
	margin-bottom: 22px;
}

.underheader__author {
	margin-bottom: 42px;
}
</style>