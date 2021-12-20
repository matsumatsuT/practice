<template>
    <section class="philosophy">
		<div class="philosophy__left">
			<div>
				<h2 class="philosophy__left-title">PHILOSOPHY</h2>
				<p class="philosophy__left-top">
					たまには、贅沢を<br>
					たまには、わがままを<br>
					たまには、ごちそうを
				</p>
				<p class="philosophy__left-bottom">
					その日仕入れた新鮮な食材を、お好きな調理法で、<br>
					ジャンルを超えた様々な料理をおとどけいたします。<br>
					美容や健康のもととなるお食事を、<br>
					楽しく、おいしくお召し上がりください。
				</p>
				<div class="philosophy__button">
					<a href="#">MORE</a>
				</div>
			</div>
		</div>
		<div class="philosophy__right"></div>
	</section>
</template>

<script>
export default {
    name: 'Philosophy'
}
</script>

<style lang="css" scoped>
.philosophy {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  height: 680px;
  background-color: #242424; }
  @media screen and (max-width: 480px) {
    .philosophy {
      -webkit-box-orient: vertical;
      -webkit-box-direction: normal;
          -ms-flex-direction: column;
              flex-direction: column; } }
  .philosophy__left, .philosophy__right {
    width: 50%; }
    @media screen and (max-width: 480px) {
      .philosophy__left, .philosophy__right {
        width: 100%; } }
  .philosophy__right {
    background: url(../assets/images/philosophy_bg.jpg) center/cover no-repeat; }
    @media screen and (max-width: 480px) {
      .philosophy__right {
        height: 230px; } }
  .philosophy__left {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    padding: 0px 10px; }
    @media screen and (max-width: 480px) {
      .philosophy__left {
        padding: 0 20px;
        width: 100%;
        height: 450px; } }
    .philosophy__left-top, .philosophy__left-bottom {
      line-height: 1.6; }
    .philosophy__left-title {
      color: #fff;
      font-size: 24px; }
      @media screen and (max-width: 480px) {
        .philosophy__left-title {
          text-align: center;
          font-size: 16px; } }
    .philosophy__left-top {
      margin-top: 40px;
      color: #fff; }
      @media screen and (max-width: 480px) {
        .philosophy__left-top {
          font-size: 12px;
          line-height: 1.8; } }
    .philosophy__left-bottom {
      margin-top: 20px;
      color: #fff; }
      @media screen and (max-width: 480px) {
        .philosophy__left-bottom {
          font-size: 12px;
          line-height: 1.8; } }
  .philosophy__button {
    margin-top: 50px;
    border: 1px solid #fff;
    width: 180px; }
    @media screen and (max-width: 480px) {
      .philosophy__button {
        width: 100%; } }
    .philosophy__button a {
      text-align: center;
      padding: 16px 0;
      font-size: 14px;
      color: #fff; }
      .philosophy__button a:hover {
        color: #242424;
        background: #fff;
    }
</style>