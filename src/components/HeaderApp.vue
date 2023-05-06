<template>
	<div>
		<header class="header">
		<div class="header__sale">
			One week only—50% off all courses with code 50OFF at checkout
		</div>
		<div class="container">
			<div class="header__inner">
				<div class="header__menu">
					<div class="header__img">
						<a href="#"><img class="header-img" src="../assets/logo.png" alt="logo"></a>
					</div>
					<nav class="menu">
						<div class="menu__btn">
							<span></span>
						</div>
						<ul class="menu__list">
							<li class="menu__list__item"><a href="#" class="menu__list__link">Courses</a></li>
							<li class="menu__list__item"><a href="#" class="menu__list__link">Free Workshops</a></li>
							<li class="menu__list__item"><a href="#" class="menu__list__link">Blog</a></li>
							<li class="menu__list__item"><a href="#" class="menu__list__link">About</a></li>
							<li class="menu__list__item"><a href="#" class="menu__list__link">Contact</a></li>
						</ul>
					</nav>
					<div class="header__button">
						<a href="#" class="header-btn"><img src="../assets/header-btn.png" alt="button"></a>
					</div>
				</div>

			</div>
		</div>
	</header>
	</div>
</template>

<script>
</script>


<style scoped>

	.header{
    background-color: #1C1C33;
    max-width: 1440px;
    margin: 0 auto;
}
.header__sale {
    font-size: 18px;
    line-height: 27px;
    color: #1C1C33;
    text-align: center;
    background-color: #57D9A6;
    width: 100%;
    height: 43px;
    display: flex;
    justify-content: center;
    align-items: center;
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

.menu__list__item + .menu__list__item{
    margin-left: 32px;
}
.menu__list__link {
    font-size: 17px;
    line-height: 27px;
    transition: all .5s;
}
.menu__list__link:hover{
    color:#57D9A6;
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
</style>