<template>
	<div v-for="item in FeaturedItems" :key="item" class="featured__list__item">
	<div class="featured__list__item__img">
		<a href="#"><img src="@/assets/featured-3.jpg" alt="foto"></a>
	</div>
	<div class="featured__list__item__text">
		<div class="featured__list__item__title">
			<a class="featured__list__item-title" href="#">{{item.title}}</a>
		</div>
		<div class="featured__list__item__author">
			<a href="#" class="default-author">{{ item.author}}</a>
		</div>
		<div class="featured__list__item__price">{{item.price}}</div>
		<div class="featured__list__item__link">
			<a href="#" class="default-learn-more">Learn More</a>
		</div>
	</div>
</div>
</template>

<script>
export default{
	data(){
		return{
			FeaturedItems: [
				{title: 'How to Increase Your Engagement on Instagram', author: 'Katie Murphy', price: '$ 59.99 USD',src: '@/assets/featured-1.jpg'},
				{title: 'Business 101: Setting up Your Taxes', author: 'Bessie Cooper', price: '$ 39.99 USD'},
				{title: 'iPhone Photography: Tips, Tricks and Best Practices', author: 'Dianne Russell', price: '$ 39.99 USD'}
			]
		}
	}
}
</script>


<style>

.featured__list__item {
	background-color: #FFF;
	width: 100%;
	max-width: 393px;
}

.featured__list__item__text {
	padding: 22px 24px 25px 24px;
}

.featured__list__item__title {
	margin-bottom: 8px;
}

.featured__list__item-title {
	font-size: 24px;
	line-height: 28.8px;
	color: #1C1C33;
}

.featured__list__item__author {
	margin-bottom: 15px;
}

.featured__list__item__price {
	font-size: 22px;
	line-height: 27px;
	color: #1C1C33;
	margin-bottom: 16px;
}

.featured__list__item__price span {
	color: #B2B2BF;
	padding-right: 8px;
}
</style>