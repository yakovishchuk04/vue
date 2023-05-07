<template>
		<header class="header">
			<HeaderSale />
		<div class="container">
			<div class="header__inner">
				<div class="header__menu">
					<div class="header__img">
						<a href="#"><img class="header-img" src="@/assets/logo.png" alt="logo"></a>
					</div>
					<nav class="menu">
						<div class="menu__btn">
							<span></span>
						</div>
						<ul class="menu__list">
							<headerItem />
						</ul>
					</nav>
					<div class="header__button">
						<a href="#" class="header-btn"><img src="../assets/header-btn.png" alt="button"></a>
					</div>
				</div>
			</div>
		</div>
	</header>
</template>

<script>
import HeaderSale from '@/components/HeaderSale.vue'
import HeaderItem from '@/components/HeaderItem.vue'
export default{	
	props: ['headerItems'],
	components: {
		HeaderSale,
		HeaderItem
	}
}
</script>

<style>

	.header{
    background-color: #1C1C33;
    max-width: 1440px;
    margin: 0 auto;
}

.header__menu {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 105px;
}
.menu__list {
    display: flex;
    justify-content: space-between;
}

.header-btn {
    position: relative;
}
.header-btn::after{
    content: "0";
    width: 18px;
    height: 18px;
    background-color: #FC5468;
    color: #FFF;
    border-radius: 9px;
    position: absolute;
    top: -12px;
    right: -5px;
    font-size: 11px;
    line-height: 18px;
    text-align: center;
}
.menu__btn {
	width: 40px;
	height: 30px;
	display: none;
	position: relative;
}

.menu__btn span {
	display: block;
	height: 2px;
	width: 100%;
	background-color: #FFF;
	position: absolute;
	left: 0;
	top: 14px;
}

.menu__btn::after,
.menu__btn::before {
	content: "";
	position: absolute;
	width: 40px;
	height: 2px;
	background-color: #FFF;
	left: 0;
}

.menu__btn::before {
	top: 0;
}

.menu__btn::after {
	bottom: 0;
}
</style>