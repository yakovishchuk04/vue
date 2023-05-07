<template>
	<section class="workshop">
			<div class="container">
				<div class="workshop__title default-title">
					Upcoming Free Workshops
				</div>
				<div class="workshop__line">
					<div class="default-line"></div>
				</div>
				<div class="workshop__text">
					Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum
					tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut commodo diam libero
					vitae erat.
				</div>
				<div class="workshop__button">
					<div class="default-btn btn-white">View All Workshops</div>
				</div>
				<div class="workshop__list">
					<WorkshopItem />
				</div>
			</div>
		</section>
</template>

<script>
import WorkshopItem from '@/components/WorkshopItem.vue'
export default{
	components: {
		WorkshopItem
	}
}
</script>

<style>

.workshop {
	margin-top: 140px;
}

.workshop__title {
	text-align: center;
	color: #1C1C33;
	margin-bottom: 17px;
}

.workshop__line {
	display: flex;
	justify-content: center;
	margin-bottom: 50px;
}

.workshop__text {
	color: #4E4E65;
	text-align: center;
	margin: 0 auto 46px auto;
	max-width: 645px;
}

.workshop__button {
	display: flex;
	justify-content: center;
	margin-bottom: 80px;
}

.workshop__list {
	display: flex;
	justify-content: space-between;
}
</style>