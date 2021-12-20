<template>
	<section class="access">
		<h2 class="access__title">ACCESS</h2>
		<div class="access__map">
			<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3241.66553052196!2d139.66499671495762!3d35.66061138019912!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6018f36bdb70683b%3A0x243faef2e21a3270!2z44CSMTU1LTAwMzEg5p2x5Lqs6YO95LiW55Sw6LC35Yy65YyX5rKi77yS5LiB55uu77yR77yZ4oiS77yV!5e0!3m2!1sja!2sjp!4v1569944678065!5m2!1sja!2sjp" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen=""></iframe>
		</div>
		<div class="access__detail">
			<dl>
				<dt>住所</dt>
				<dd>〒155-0031 東京都世田谷区北沢２丁目１９−５</dd>
			</dl>
			<dl>
				<dt>アクセス</dt>
				<dd>
					<div>井の頭線「下北沢駅」東口より徒歩1分</div>
					<div>小田急小田原線「下北沢駅」東口より徒歩1分</div>
				</dd>
			</dl>
			<dl>
				<dt>営業時間</dt>
				<dd>平日：10:30〜19:30</dd>
			</dl>
			<dl>
				<dt>定休日</dt>
				<dd>土曜・日曜・祝日</dd>
			</dl>
		</div>
	</section>
</template>

<script>
export default {
    name: 'Access'
}
</script>

<style lang="css" scoped> 
.access {
  background: #f0f0f0;
  padding: 100px 0; }
  @media screen and (max-width: 480px) {
    .access {
      padding: 50px 0; } }
  .access__title {
    text-align: center;
    font-size: 24px; }
  .access__map {
    margin-top: 50px; }
    .access__map iframe {
      width: 100%; }
  .access__detail {
    width: 50%;
    margin: 0 auto;
    margin: 40px auto 0; }
    @media screen and (max-width: 480px) {
      .access__detail {
        width: 80%; } }
    .access__detail dl {
      display: -webkit-box;
      display: -ms-flexbox;
      display: flex; }
      @media screen and (max-width: 480px) {
        .access__detail dl {
          -webkit-box-orient: vertical;
          -webkit-box-direction: normal;
              -ms-flex-direction: column;
                  flex-direction: column; } }
      .access__detail dl:not(:first-child) {
        margin-top: 30px; }
        @media screen and (max-width: 480px) {
          .access__detail dl:not(:first-child) {
            margin-top: 40px; } }
      .access__detail dl dt {
        -webkit-box-flex: 1;
            -ms-flex: 1;
                flex: 1;
        font-size: 14px; }
        @media screen and (max-width: 480px) {
          .access__detail dl dt {
            font-weight: bold;
            font-size: 14px;
            margin-bottom: 8px; } }
      .access__detail dl dd {
        -webkit-box-flex: 2;
            -ms-flex: 2;
                flex: 2;
        font-size: 14px; }
        .access__detail dl dd div:not(:first-child) {
            margin-top: 10px;
        }
</style>