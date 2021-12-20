<template>
	<header class="header">
		<ul class="header__sns">
			<li><a href="#"><img src="../assets/images/sns01.png" alt=""></a></li>
			<li><a href="#"><img src="../assets/images/sns02.png" alt=""></a></li>
		</ul>
		<ul class="header__navi">
			<li><a href="#">PHILOSOPHY</a></li>
			<li><a href="#">NEWS</a></li>
			<li><a href="#">MENU</a></li>
			<li><a href="#">ACCESS</a></li>
			<li><a href="#">CONTACT</a></li>
		</ul>
	</header>
</template>

<script>
export default {
    name: 'MyHeader'
}
</script>

<style lang="css" scoped>
.header {
    position: fixed;
    top: 0;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: justify;
        -ms-flex-pack: justify;
            justify-content: space-between;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    width: 100%;
    z-index: 1;
    padding: 10px 20px;
    background: rgba(0, 0, 0, 0.6);
}
@media screen and (max-width: 480px) {
    .header {
        padding: 20px 0 20px;
        -webkit-box-pack: center;
        -ms-flex-pack: center;
        justify-content: center;
    } 
}
.header__navi {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
}
.header__navi li:not(:last-child) {
    margin-right: 14px;
}
.header__navi a {
    color: #fff;
    font-size: 12px;
}
.header__sns {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
}
@media screen and (max-width: 480px) {
    .header__sns {
        display: none;
        } 
}
.header__sns li {
    width: 45px;
    height: 45px;
}


</style>