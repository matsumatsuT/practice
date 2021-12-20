<template>
    <footer class="footer">
		<div class="footer__inner">
			<ul class="footer__inner-navi">
				<li><a href="#">PHILOSOPHY</a></li>
				<li><a href="#">NEWS</a></li>
				<li><a href="#">MENU</a></li>
				<li><a href="#">CONTACT</a></li>
			</ul>
			<div class="footer__inner-sns">
				<ul>
					<li><a href="#"><img src="../assets/images/sns01.png" alt=""></a></li>
					<li><a href="#"><img src="../assets/images/sns02.png" alt=""></a></li>
				</ul>
				<div class="copyright">© 2019 CRI Inc</div>
			</div>
		</div>
	</footer>
</template>

<script>
export default {
    name: 'MyFooter'
}
</script>

<style lang="css" scoped>
.footer {
    background-color: #242424;
}
.footer__inner {
    width: 80%;
    margin: auto;
    padding: 50px 0;
}
.footer__inner-navi {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    margin-bottom: 30px;
}
@media screen and (max-width: 480px) {
    .footer__inner-navi {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-orient: vertical;
        -webkit-box-direction: normal;
            -ms-flex-direction: column;
                flex-direction: column;
        -webkit-box-align: center;
            -ms-flex-align: center;
                align-items: center; 
    }
}
.footer__inner-navi li {
    margin: 0 10px;
}
@media screen and (max-width: 480px) {
    .footer__inner-navi li:not(:last-child) {
        margin-bottom: 10px;
    }
}
.footer__inner-navi li a {
    color: #ffffff;
    font-size: 12px;
}
@media screen and (max-width: 480px) {
    .footer__inner-navi li a {
        padding: 10px 0;
    }
}
.footer__inner-sns {
    border-top: 1px solid #7c7c7c;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: justify;
        -ms-flex-pack: justify;
            justify-content: space-between;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    padding-top: 30px; 
}
.footer__inner-sns ul {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
}
.footer__inner-sns ul li {
    width: 40px;
    height: 40px;
}
.footer .copyright {
    color: #ffffff;
    font-size: 12px;
}
</style>