<template>
	<div v-for="item in WorkshopItems" :key="item" class="workshop__list__item">
	<div class="workshop__list__item-title">{{item.title}}</div>
	<div class="workshop__list__item-text">{{item.desc}}
	</div>
	<div class="workshop__list__item-btn">
		<a href="#" class="default-learn-more">Learn More</a>
	</div>
</div>
</template>

<script>
export default{
	data(){
		return{
		WorkshopItems: [
			{title: 'Photography Basics',desc: 'Lorem ipsum dolor sit amet, consectetur adipiscing elitut aliquam, purus sit amet luctus venenatis, lectus magna fringilla urna, porttitor rhoncusdolor purus non enim praesent elementum facilisis leo.'},
			{title: 'Business 101',desc: 'Lorem ipsum dolor sit amet, consectetur adipiscing elitut aliquam, purus sit amet luctus venenatis, lectus magna fringilla urna, porttitor rhoncusdolor purus non enim praesent elementum facilisis leo.'},
			{title: 'Social Networking Camp',desc: 'Lorem ipsum dolor sit amet, consectetur adipiscing elitut aliquam, purus sit amet luctus venenatis, lectus magna fringilla urna, porttitor rhoncusdolor purus non enim praesent elementum facilisis leo.'}
		]
	}
}
}
</script>

<style>

.workshop__list__item {
	padding: 22px 24px;
	width: 100%;
	max-width: 391px;
}

.workshop__list__item-title {
	font-size: 24px;
	line-height: 28.8px;
	color: #1C1C33;
	margin-bottom: 10px;
	font-weight: 700;
}

.workshop__list__item-text {
	font-size: 18px;
	line-height: 27px;
	color: #4E4E65;
	margin-bottom: 29px;
}
</style>