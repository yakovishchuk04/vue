<template>
		<HeaderApp />
		<main>
			<UnderHeader />
			<FeaturedApp />
			<RecomendationApp />
			<WorkshopApp />
			<TeachingApp />
			<ArticlesApp />
		</main>
		<FooterApp />
</template>


<script>
import HeaderApp from '@/components/HeaderApp.vue'
import UnderHeader from '@/components/UnderHeader.vue'
import FeaturedApp from '@/components/FeuturedApp.vue'
import RecomendationApp from '@/components/RecomendationApp.vue'
import WorkshopApp from '@/components/WorkshopApp.vue'
import TeachingApp from '@/components/TeachingApp.vue'
import ArticlesApp from '@/components/ArticlesApp.vue'
import FooterApp from '@/components/FooterApp.vue'
export default {
  name: 'App',
  components: {
		HeaderApp,
		UnderHeader,
		FeaturedApp,
		RecomendationApp,
		WorkshopApp,
		TeachingApp,
		ArticlesApp,
		FooterApp
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@400;700&display=swap');
	*,
	*::after,
	*::before{ 
		box-sizing: border-box;
	}
	#app{
    font-family: 'Source Sans Pro', sans-serif;
    font-size: 22px;
    line-height: 33px;
    color: #F6F6F8;
	}
	a{
    text-decoration: none;
    color: inherit;
	}
	ul{
		padding-inline-start: 0px;
	}
	li{
		list-style: none;
	}
	.btn-black:hover {
	color: #57D9A6;
	background-color: #161631;
}

.btn-black-two:hover {
	color: #57D9A6;
	background-color: #303064;
}

.btn-white:hover {
	color: #57D9A6;
	background-color: #1C1C33;
}
.container {
    max-width: 1296px;
    margin: 0 auto;
    padding: 0 10px;  
}
.default-title{
    font-size: 44px;
    font-weight: 700;
    line-height: 52.8px;
}
.default-line{
    width: 100%;
    max-width: 150px;
    height: 2px;
    background-color: #57D9A6;

}
.default-author {
    font-size: 17px;
    line-height: 27px;
    color: #4E4E65;
}
.default-btn {
    font-size: 18px;
    line-height: 27px;
    letter-spacing: 1px;
    color: #1C1C33;
    background-color: #57D9A6;
    padding: 16px 24px;
    border-radius: 4px;
    text-transform: uppercase;
    cursor: pointer;
    transition: all .5s;
}
.default-learn-more {
    text-transform: uppercase;
    font-size: 16px;
    line-height: 20.8px;
    color:#57D9A6;
    letter-spacing: 1px;
    transition: all .6s;
}
.default-learn-more:hover{
    color:#23233B;
}
</style>
