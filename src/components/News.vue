<template>
	<section class="news">
		<h2 class="news__title">NEWS<span>今日のおすすめ食材などニュースを発信</span></h2>
		<ul class="news__list">
			<li>
				<a href="#">
					<div class="news__list-img">
						<img src="../assets/images/news01.jpg" alt="">
					</div>
					<div class="news__list-txt">
						<dl>
							<dt>夏季休業のお知らせ</dt>
							<dd>Jul 18,2019</dd>
						</dl>
					</div>
				</a>
			</li>
			<li>
				<a href="#">
					<div class="news__list-img">
						<img src="../assets/images/news02.jpg" alt="">
					</div>
					<div class="news__list-txt">
						<dl>
							<dt>夏季休業のお知らせ</dt>
							<dd>Jul 18,2019</dd>
						</dl>
					</div>
				</a>
			</li>
			<li>
				<a href="#">
					<div class="news__list-img">
						<img src="../assets/images/news03.jpg" alt="">
					</div>
					<div class="news__list-txt">
						<dl>
							<dt>夏季休業のお知らせ</dt>
							<dd>Jul 18,2019</dd>
						</dl>
					</div>
				</a>
			</li>
		</ul>
		<div class="news__button">
			<a href="#">MORE</a>
		</div>
	</section>
</template>

<script>
export default {
    name: 'News'
}
</script>

<style lang="css" scoped>
.news {
  background: #F0F0F0;
  padding: 100px 0; }
  @media screen and (max-width: 480px) {
    .news {
      padding: 50px 0; } }
  .news__title {
    width: 90%;
    margin: 0 auto;
    font-size: 24px; }
    @media screen and (max-width: 480px) {
      .news__title {
        font-size: 16px;
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-orient: vertical;
        -webkit-box-direction: normal;
            -ms-flex-direction: column;
                flex-direction: column;
        text-align: center; } }
    .news__title span {
      font-size: 16px;
      margin-left: 16px; }
      @media screen and (max-width: 480px) {
        .news__title span {
          font-size: 12px;
          margin-top: 10px; } }
  .news__list {
    width: 90%;
    margin: 0 auto;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    margin-top: 40px; }
    @media screen and (max-width: 480px) {
      .news__list {
        -ms-flex-wrap: wrap;
            flex-wrap: wrap; } }
    .news__list li {
      width: calc(100% / 4 - 15px); }
      @media screen and (max-width: 480px) {
        .news__list li {
          width: calc(100% / 2 - 2%); }
          .news__list li:nth-child(odd) {
            margin-right: 4%; }
          .news__list li:nth-child(n+3) {
            margin-top: 24px; } }
      .news__list li:not(:last-child) {
        margin-right: 30px; }
        @media screen and (max-width: 480px) {
          .news__list li:not(:last-child) {
            margin-right: 0; } }
    .news__list-txt {
      margin-top: 10px;
      font-size: 14px; }
      .news__list-txt dd {
        margin-top: 10px; }
  .news__button {
    border: 1px solid #242424;
    width: 180px;
    margin: 60px auto 0; }
    @media screen and (max-width: 480px) {
      .news__button {
        width: 90%; } }
    .news__button a {
      text-align: center;
      padding: 16px 0;
      font-size: 14px;
      color: #242424; }
      .news__button a:hover {
        color: #fff;
        background: #242424;
    }
</style>