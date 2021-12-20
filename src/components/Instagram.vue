<template>
    <section class="instagram">
		<h2 class="instagram__title">INSTAGRAM</h2>
		<ul class="instagram__list">
			<li>
				<a href="#">
					<div class="instagram__list-img">
						<img src="../assets/images/news01.jpg" alt="">
					</div>
				</a>
			</li>
			<li>
				<a href="#">
					<div class="instagram__list-img">
						<img src="../assets/images/news02.jpg" alt="">
					</div>
				</a>
			</li>
			<li>
				<a href="#">
					<div class="instagram__list-img">
						<img src="../assets/images/news03.jpg" alt="">
					</div>
				</a>
			</li>
			<li>
				<a href="#">
					<div class="instagram__list-img">
						<img src="../assets/images/news03.jpg" alt="">
					</div>
				</a>
			</li>
		</ul>
		<div class="instagram__button">
			<a href="#">FOLLOW US</a>
		</div>
	</section>

</template>

<script>
export default {
    name: 'Instagram'
}
</script>

<style lang="scss" scoped>
.instagram {
  background: #fff;
  padding: 100px 0; }
  @media screen and (max-width: 480px) {
    .instagram {
      width: 100%;
      padding: 50px 0; } }
  .instagram__title {
    width: 90%;
    margin: 0 auto;
    font-size: 24px; }
    @media screen and (max-width: 480px) {
      .instagram__title {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-orient: vertical;
        -webkit-box-direction: normal;
            -ms-flex-direction: column;
                flex-direction: column;
        text-align: center;
        font-size: 16px; } }
    .instagram__title span {
      font-size: 16px;
      margin-left: 16px; }
      @media screen and (max-width: 480px) {
        .instagram__title span {
          margin-top: 10px;
          font-size: 12px; } }
  .instagram__list {
    width: 90%;
    margin: 0 auto;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    margin-top: 40px; }
    @media screen and (max-width: 480px) {
      .instagram__list {
        -ms-flex-wrap: wrap;
            flex-wrap: wrap; }
        .instagram__list:nth-child(odd) {
          margin-right: 4%; }
        .instagram__list:nth-child(n+3) {
          margin-top: 24px; } }
    .instagram__list li {
      width: calc(100% / 4 - 15px); }
      @media screen and (max-width: 480px) {
        .instagram__list li {
          width: calc(100% / 2 - 2%); } }
      .instagram__list li:not(:last-child) {
        margin-right: 30px; }
        @media screen and (max-width: 480px) {
          .instagram__list li:not(:last-child) {
            margin-right: 0; } }
  .instagram__button {
    border: 1px solid #242424;
    width: 180px;
    margin: 60px auto 0; }
    @media screen and (max-width: 480px) {
      .instagram__button {
        width: 90%; } }
    .instagram__button a {
      text-align: center;
      padding: 16px 0;
      font-size: 14px;
      color: #242424; }
      .instagram__button a::hover {
        color: #fff;
        background: #242424;
    }

</style>