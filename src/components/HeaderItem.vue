<template>
	<li class="menu__list-item"><a href="#" class="menu__list-link">Courses</a></li>
	<li class="menu__list-item"><a href="#" class="menu__list-link">Free Workshops</a></li>
	<li class="menu__list-item"><a href="#" class="menu__list-link">Blog</a></li>
	<li class="menu__list-item"><a href="#" class="menu__list-link">About</a></li>
	<li class="menu__list-item"><a href="#" class="menu__list-link">Contact</a></li>
</template>

<script>
export default{
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