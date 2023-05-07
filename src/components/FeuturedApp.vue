<template>
	<section class="featured">
			<div class="container">
				<div class="featured__inner">
					<div class="featured__title default-title">Featured Courses</div>
					<div class="featured__line">
						<div class="default-line"></div>
					</div>
					<div class="featured__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse
						varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor
						interdum nulla, ut commodo diam libero vitae erat.
					</div>
					<div class="featured__button">
						<a href="#" class="default-btn btn-black">View All Courses</a>
					</div>
					<div class="featured__list">
						<FeaturedItem />
					</div>
				</div>
			</div>
		</section>
</template>

<script>
import FeaturedItem from '@/components/FeaturedItem'
export default{
	components: {
		FeaturedItem
	}

}
</script>


<style>

.featured {
	background-color: #23233B;
	padding-top: 144px;
	margin: 0 auto;
	max-width: 1440px;
	padding-bottom: 144px;
}

.featured__title {
	margin-bottom: 17px;
	text-align: center;
}

.featured__line {
	margin-bottom: 50px;
	display: flex;
	justify-content: center;
}

.featured__text {
	text-align: center;
	max-width: 644px;
	margin: 0 auto 46px auto;
}

.featured__button {
	display: flex;
	justify-content: center;
	margin-bottom: 80px;
}

.featured__list {
	display: flex;
	justify-content: space-between;
}
</style>