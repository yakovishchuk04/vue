<template>
	<li v-for="item in HeaderItems" :key="item" class="menu__list-item"><a href="#" class="menu__list-link">{{item.title}}</a></li>
</template>

<script>
export default{
	name: 'HeaderItem',
	data(){
		return{
			HeaderItems: [
				{title: 'Courses'},
				{title: 'Free Workshops'},
				{title: 'Blog'},
				{title: 'About'},
				{title: 'Contact'}
			]
		}
	}
}
</script>







<style>
.menu__list-item + .menu__list-item{
    margin-left: 32px;
}
.menu__list-link {
    font-size: 17px;
    line-height: 27px;
    transition: all .5s;
}
.menu__list-link:hover{
    color:#57D9A6;
}
</style>