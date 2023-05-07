<template>
	<section class="form">
			<div class="container">
				<div class="form__inner">
					<div class="form-title default-title">You have the power to define your future.</div>
					<form action="">
						<input class="form-email" type="email" placeholder="email address">
						<button class="form-submit" type="submit">submit</button>
					</form>
				</div>
			</div>
		</section>
	<footer class="footer">
		<div class="container">
			<div class="footer__inner">
				<div class="footer__img">
					<a href="#"><img class="footer-img" src="@/assets/logo.png" alt="logo"></a>
				</div>
				<div class="footer__list">
					<div class="footer__list__item">
						<ul>
							<li class="footer-title">learning Platform</li>
							<li class="footer-item"><a class="footer-link" href="#">Home</a></li>
							<li class="footer-item"><a class="footer-link" href="#">Courses</a></li>
							<li class="footer-item"><a class="footer-link" href="#">Free Workshops</a></li>
							<li class="footer-item"><a class="footer-link" href="#">Blog</a></li>
							<li class="footer-item"><a class="footer-link" href="#">About</a></li>
							<li class="footer-item"><a class="footer-link" href="#">Contact</a></li>
						</ul>
					</div>
					<div class="footer__list__item">
						<ul>
							<li class="footer-title">Template</li>
							<li class="footer-item"><a class="footer-link" href="#">Instructions</a></li>
							<li class="footer-item"><a class="footer-link" href="#">Style Guide</a></li>
							<li class="footer-item"><a class="footer-link" href="#">Licenses</a></li>
							<li class="footer-item"><a class="footer-link" href="#">Changelog</a></li>
						</ul>
					</div>
					<div class="footer__list__item--images">
						<li class="footer-title">Follow skillz</li>
						<div class="footer__list__item--images__list">
							<a href="#"><img src="@/assets/footer-1.png" alt="icon"></a>
							<a href="#"><img src="@/assets/footer-2.png" alt="icon"></a>
							<a href="#"><img src="@/assets/footer-3.png" alt="icon"></a>
							<a href="#"><img src="@/assets/footer-4.png" alt="icon"></a>
							<a href="#"><img src="@/assets/footer-5.png" alt="icon"></a>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="footer__bottom">
			<div class="container">
				<div class="footer__bottom__inner">
					<a href="#">© Skillz Template</a>
					<a href="#"><span>Powered by Webflow</span> </a>
				</div>
			</div>
		</div>
	</footer>
</template>

<script>

</script>

<style>

.form {
	position: relative;
	top: 160px;
}

.form__inner {
	background-color: #57D9A6;
	border-radius: 4px;
	padding-bottom: 95px;
}

.form-title {
	color: #1C1C33;
	text-align: center;
	margin-bottom: 57px;
	padding-top: 80px;
}

.form__inner form {
	display: flex;
	justify-content: center;
}

.form-email {
	padding: 5px 20px;
	background-color: transparent;
	width: 100%;
	max-width: 532px;
	height: 64px;
	border-radius: 4px;
	border: 1px solid #1C1C33;
	font-family: 'Source Sans Pro', sans-serif;
	font-size: 22px;
	line-height: 33px;
}

.form-email::placeholder {
	font-size: 20px;
	line-height: 20px;
	color: #1C1C33;
	text-transform: uppercase;
	font-weight: 700;
	font-family: 'Source Sans Pro', sans-serif;
}

.form-submit {
	color: #57D9A6;
	font-size: 20px;
	line-height: 10px;
	text-transform: uppercase;
	font-weight: 700;
	background-color: #1C1C33;
	border-radius: 4px;
	padding: 25px 24px;
	cursor: pointer;
	border: none;
	margin-left: 16px;
	transition: all .5s;
}

.form-submit:hover {
	opacity: 80%;
}

.footer {
	background-color: #1C1C33;
	max-width: 1440px;
	margin: 0 auto;
	padding-top: 320px;

}

.footer__inner {
	padding-bottom: 140px;
}

.footer__list {
	display: flex;
	justify-content: flex-start;
	margin-top: 80px;
}

.footer__list__item+.footer__list__item {
	margin-left: 170px;
}

.footer__list__item ul {
	list-style-type: none;
}

.footer-title {
	font-size: 16px;
	line-height: 20.8px;
	letter-spacing: 1px;
	text-transform: uppercase;
	margin-bottom: 23px;
}

.footer__list__item--images {
	margin-left: 170px;
}

.footer__list__item--images li {
	font-weight: 700;
	list-style-type: none;
}

.footer-item {
	transition: all .5s;
}

.footer-item:hover {
	color: #57D9A6;
}

.footer-item+.footer-item {
	margin-top: 16px;
}

.footer-link {
	font-size: 18px;
	line-height: 27px;
}

.footer__list__item--images__list a+a {
	margin-left: 16px;
}

.footer__bottom {
	max-width: 1440px;
	margin: 0 auto;
	background-color: #23233B;
}

.footer__bottom__inner a {
	transition: all .5s;
}

.footer__bottom__inner a:hover {
	color: #57D9A6;
}

.footer__bottom__inner {
	color: #B2B2BF;
	font-size: 16px;
	line-height: 24px;
	height: 56px;
	display: flex;
	justify-content: flex-start;
	align-items: center;
}

.footer__bottom__inner span {
	margin-left: 32px;
}
</style>