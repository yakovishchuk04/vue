<template>
	<section class="articles">
			<div class="container">
				<div class="articles__inner">
					<div class="acticles-title default-title">Recent Articles</div>
					<div class="articles__line">
						<div class="default-line"></div>
					</div>
					<div class="articles__text">
						Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros
						elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut commodo
						diam libero vitae erat.
					</div>
					<div class="articles__button">
						<a href="#" class="default-btn btn-white">View all articles</a>
					</div>
					<div class="articles__list">
						<ArticlesItem />
					</div>
				</div>
			</div>
		</section>
</template>

<script>
import ArticlesItem from '@/components/ArticlesItem.vue'
export default{
	components:{
		ArticlesItem
	}
}
</script>

<style>
.articles {
	margin-top: 142px;
}

.acticles-title {
	text-align: center;
	color: #1C1C33;
	margin-bottom: 17px;
}

.articles__line {
	display: flex;
	justify-content: center;
	margin-bottom: 50px;
}


.articles__text {
	margin: 0 auto 46px auto;
	max-width: 650px;
	text-align: center;
	color: #4E4E65;
}

.articles__button {
	display: flex;
	justify-content: center;
	margin-bottom: 80px;
}

.articles__list {
	display: flex;
	justify-content: space-between;
}
</style>