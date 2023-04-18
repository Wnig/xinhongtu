<template>
  <div class="home">
  	<div class="pc">
		<div class="selection selection-1">
			<video class="video1" src="../assets/video_01.mp4" autoplay="autoplay" loop="loop"></video>
			<div class="con">
				<app-header></app-header>
			  	<div class="cont">
				  	<div class="cont_">
				  		<div class="c_tit">
				  			<img src="../assets/3.svg" alt="">
				  		</div>
				  		<h3>光大旅游战略合作伙伴</h3>
				  		<div class="down-con" @click="slideDown">
					  		<div class="down">
					  		</div>
				  		</div>
				  	</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-2">
			<div class="con">
			  	<div class="cont">
			  		<img src="../assets/8.svg" alt="">
				  	<h1>关于欣宏途</h1>
				  	<p>欣宏途旅游，整合境内外优质旅游产品及周边服务资源，通过社交网络所形成的人际脉络形成新的行为冲动和内在需求，形成在线旅游新模式；建立人人“享优惠”，分享“享收益”的全民旅游营销新生态，实现自买省钱、分享赚钱的运营目标；打造互联网时代社交旅游电商综合平台！</p>
				  	<div class="pathCons">
					  	<svg id="plane" xmlns="http://www.w3.org/2000/svg" width="1920" height="197" viewBox="0 0 1920 197">
							<g fill="none" fill-rule="evenodd" transform="translate(-2)">
							    <path stroke="#979797" stroke-dasharray="5" d="M0,196.626486 C311.412034,66.2088287 631.83522,1 961.269555,1 C1290.70389,1 1611.12708,66.2088287 1922.53911,196.626486"/>
							</g>
						</svg>
						<svg id="planes" xmlns="http://www.w3.org/2000/svg" width="1920" height="197" viewBox="0 0 1920 197">
							<g fill="none" fill-rule="evenodd" transform="translate(-2)">
								<path id="planePath" fill="#000" fill-rule="nonzero" d="M38,29.0407002 L38,25.6246779 L22.4537164,15.3740336 L22.4537164,3.41602238 C22.4537164,3.41602238 22.4537164,0 19,0 C15.5449808,0 15.5449808,3.41602238 15.5449808,3.41602238 L15.5449808,15.3740336 L0,25.6246779 L0,29.0407002 L15.5449808,23.9147338 L15.5449808,33.4837199 L10.3637548,37.5839776 L10.3637548,41 L19,37.5839776 L27.6362452,41 L27.6362452,37.5839776 L22.4537164,33.4837199 L22.4537164,23.9147338 L38,29.0407002 Z">
									<animateMotion path="M0,196.626486 C311.412034,66.2088287 631.83522,1 961.269555,1 C1290.70389,1 1611.12708,66.2088287 1922.53911,196.626486" begin="0s" dur="10s" rotate="auto-reverse" repeatCount="indefinite">
							    	</animateMotion>
								</path>
							</g>
						</svg>
				  	</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-3">
			<video class="video1" src="../assets/video_02.mp4" autoplay="autoplay" loop="loop"></video>
			<div class="con">
			  	<div class="cont">
			  		<div class="left-con">
			  			<div class="left">
			  				<div class="left_">
				  				<h3>平台打造全民旅游<br/>营销新生态</h3>
				  				<div class="tag tag_01">
				  					<span>自买省钱</span><span>分享赚钱</span>
				  				</div>
								<h3>整合全渠道优质旅游产品</h3>
				  				<div class="tag tag_02">
				  					<span>价格低</span><span>服务好</span><span>产品优</span>
				  				</div>
				  				<!-- <img src="../assets/13.svg" alt=""> -->
			  				</div>
			  			</div>
			  		</div>
			  		<div class="right">
			  			<div class="right_bg">
			  				<img src="../assets/14.svg" alt="">
			  				<h1>Global visa<br/>Fast handling.</h1>
			  			</div>
			  		</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-4">
			<div class="con">
			  	<div class="cont">
			  		<h2>平台展示</h2>
			  		<div class="pictureSlider poster-main list-con">
						<div class="poster-btn poster-prev-btn"></div>
						<ul id="zturn" class="poster-list clearfix">
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/16.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/19.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/20.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/18.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/17.png" alt="">
					  			</div>
							</li>
						</ul>
					</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-5">
			<div class="con">
			  	<div class="cont">
			  		<h2>产品服务</h2>
			  		<div class="conts">
				  		<div class="floatcon">
				  			<div class="list_div list_div_01">
				  				<div class="list_div_">
				  					<img src="../assets/26.jpg" alt="">
				  					<p>国内游</p>
				  				</div>
				  			</div>
				  			<div class="list_div list_div_02">
				  				<div class="list_div_">
				  					<img src="../assets/27.jpg" alt="">
				  					<p>出境游</p>
				  				</div>
				  			</div>
				  			<div class="list_div list_div_03">
				  				<div class="list_div_">
				  					<img src="../assets/28.jpg" alt="">
				  					<p>周边游</p>
				  				</div>
				  			</div>
				  			<div class="list_div list_div_04">
				  				<div class="list_div_">
				  					<img src="../assets/dingz.svg" alt="">
				  					<p>订制</p>
				  				</div>
				  			</div>
				  			<div class="list_div list_div_05">
				  				<div class="list_div_">
				  					<img src="../assets/29.jpg" alt="">
				  					<p>签证</p>
				  				</div>
				  			</div>
				  		</div>
				  		<svg id="pathsCon" width="1920px" viewBox="0 0 1920 653" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
						    <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
						        <g id="paths" transform="translate(0.000000, -4561.000000)" stroke="#62C8F2" stroke-width="7">
						            <g id="Group-42" transform="translate(-4.000000, 4561.000000)">
						                <g id="Group-43" transform="translate(0.000000, 1.000000)">
						                    <path d="M0,0 C98.8756532,149.12456 130.374724,337.390966 139.05615,391.566386 C147.737576,445.741807 154.21174,547.736786 269.597859,533.876395 C384.983978,520.016005 434.994922,498.282186 422.618413,547.736786 C410.241904,597.191386 420.303861,689.430866 475.192802,627.359048 C530.081744,565.28723 578.212757,414.774634 666.043913,504.095499 C724.598017,563.642742 768.843982,522.160283 798.781808,379.648124 C820.337276,299.907679 875.243418,299.907679 963.500234,379.648124 C1095.88546,499.25879 1168.44677,482.349173 1229.34871,438.467145 C1290.25065,394.585116 1371.95533,432.023045 1455.35172,489.879916 C1538.7481,547.736786 1717.75165,552.4532 1811.50809,454.802708 C1874.01239,389.70238 1912.84302,330.505515 1928,277.212113" id="Path-3"></path>
						                </g>
						            </g>
						        </g>
						    </g>
						</svg>
			  		</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-6">
			<div class="con">
			  	<div class="list_div list_bg_01">
			  		<div class="list_bg"></div>
			  		<div class="list_div_">
				  		<img class="card-img" src="../assets/32.svg" alt="">
				  		<h3>如何开通旅行社？</h3>
				  		<h4>免费开通个人旅行社，共享平台1000款好物！</h4>
			  		</div>
			  	</div>
			  	<div class="list_div list_bg_02">
			  		<div class="list_bg"></div>
			  		<div class="list_div_">
				  		<img class="card-img" src="../assets/33.svg" alt="">
				  		<h3>如何获得收益？</h3>
				  		<h4>可获得20%-60%的利润奖励</h4>
				  		<p>分享商品——好友——购买成功<br/>粉丝、好友——个人旅游平台——购买成功</p>
			  		</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-7">
			<div class="con">
			  	<div class="cont">
			  		<h2>目标群体</h2>
			  		<div class="list_con">
			  			<div class="list_div">
			  				<div class="list_div_">
				  				<div class="list_bg list_bg_01"></div>	
			  					<p>旅行达人</p>
			  				</div>
			  			</div>
			  			<div class="list_div">
			  				<div class="list_div_">
				  				<div class="list_bg list_bg_02"></div>	
			  					<p>微商群体</p>
			  				</div>
			  			</div>
			  			<div class="list_div">
			  				<div class="list_div_">
				  				<div class="list_bg list_bg_03"></div>	
			  					<p>上班族</p>
			  				</div>
			  			</div>
			  			<div class="list_div">
			  				<div class="list_div_">
				  				<div class="list_bg list_bg_04"></div>	
			  					<p>学生党</p>
			  				</div>
			  			</div>
			  			<div class="list_div">
			  				<div class="list_div_">
				  				<div class="list_bg list_bg_05"></div>	
			  					<p>自由职业者</p>
			  				</div>
			  			</div>
			  			<div class="list_div">
			  				<div class="list_div_">
				  				<div class="list_bg list_bg_06"></div>	
			  					<p>全职妈妈</p>
			  				</div>
			  			</div>
			  		</div>
			  	</div>	
			</div>
		</div>
		<div class="selection selection-8">
		  	<div class="con">
				<div class="cont">
					<img class="icon" src="../assets/21.svg" alt="">
					<div class="tit-con">
						<h1>免费开通线上旅行社，日赚<strong>¥1000</strong><br/>扫码体验小程序，分享模式立即启动</h1>
					</div>
					<img class="code" src="../assets/42.png" alt="">
				</div>
		  	</div>
			<app-footer></app-footer>
		</div>
	</div>
	<div class="mob">
		<div class="selection selection-1">
			<img class="video1" src="../assets/video_01.gif"></img>
			<div class="con">
				<app-header></app-header>
			  	<div class="cont">
				  	<div class="cont_">
				  		<div class="c_tit">
				  			<img src="../assets/3.svg" alt="">
				  		</div>
				  		<h3>光大旅游战略合作伙伴</h3>
				  		<div class="down-con" @click="slideDown">
					  		<div class="down">
					  		</div>
				  		</div>
				  	</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-2">
			<div class="con">
			  	<div class="cont">
			  		<img src="../assets/8.svg" alt="">
				  	<h1>关于欣宏途</h1>
				  	<p>欣宏途旅游，整合境内外优质旅游产品及周边服务资源，通过社交网络所形成的人际脉络形成新的行为冲动和内在需求，形成在线旅游新模式；建立人人“享优惠”，分享“享收益”的全民旅游营销新生态，实现自买省钱、分享赚钱的运营目标；<br/><strong>打造互联网时代社交旅游电商综合平台！</strong></p>
				  	<div class="pathCons">
				  		<svg id="plane" xmlns="http://www.w3.org/2000/svg" width="373" height="36" viewBox="0 0 373 36">
						  <g fill="none" fill-rule="evenodd" transform="translate(-23 1)">
						    <path stroke="#979797" stroke-dasharray="5" d="M0,43 C68.0314142,14.3333333 138.031414,9.02345768e-16 210,0 C281.968586,0 351.968586,14.3333333 420,43"/>
						  </g>
						</svg>
						<svg id="planes" xmlns="http://www.w3.org/2000/svg" width="373" height="36" viewBox="0 0 373 36">
						  <g fill="none" fill-rule="evenodd" transform="translate(-23 1)">
						    <path id="planePath" fill="#000" fill-rule="nonzero" d="M23.1344553,17.6800206 L23.1344553,15.6003412 L13.6698552,9.35973402 L13.6698552,2.0796794 C13.6698552,2.0796794 13.6698552,0 11.5672277,0 C9.46380695,0 9.46380695,2.0796794 9.46380695,2.0796794 L9.46380695,9.35973402 L0,15.6003412 L0,17.6800206 L9.46380695,14.5593248 L9.46380695,20.3849374 L6.30946901,22.8811803 L6.30946901,24.9608597 L11.5672277,22.8811803 L16.8249863,24.9608597 L16.8249863,22.8811803 L13.6698552,20.3849374 L13.6698552,14.5593248 L23.1344553,17.6800206 Z">
						    	<animateMotion path="M0,43 C68.0314142,14.3333333 138.031414,9.02345768e-16 210,0 C281.968586,0 351.968586,14.3333333 420,43" begin="0s" dur="10s" rotate="auto-reverse" repeatCount="indefinite">
							    </animateMotion>
						    </path>
						  </g>
						</svg>
				  	</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-3">
			<img class="video1" src="../assets/video_02.gif"></img>
			<div class="con">
			  	<div class="cont">
			  		<div class="left-con">
			  			<div class="left">
			  				<h3>平台打造全民旅游<br/>营销新生态</h3>
			  				<div class="tag tag_01">
			  					<span>自买省钱</span><span>分享赚钱</span>
			  				</div>
							<h3>整合全渠道优质旅游产品</h3>
			  				<div class="tag tag_02">
			  					<span>价格低</span><span>服务好</span><span>产品优</span>
			  				</div>
			  				<!-- <img src="../assets/13.svg" alt=""> -->
			  			</div>
			  		</div>
			  		<div class="right">
			  			<div class="right_bg">
			  			</div>
			  		</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-4">
			<div class="con">
			  	<div class="cont">
			  		<h2>平台展示</h2>
			  		<div class="pictureSlider poster-main list-con">
						<div class="poster-btn poster-prev-btn"></div>
						<ul id="zturns" class="poster-list clearfix">
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/16.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/19.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/20.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/18.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/17.png" alt="">
					  			</div>
							</li>
						</ul>
					</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-5">
			<div class="con">
			  	<div class="cont">
			  		<h2>产品服务</h2>
			  		<div class="conts">
				  		<div class="floatcon">
				  			<div class="list_div list_div_01">
				  				<div class="list_div_">
				  					<img src="../assets/26.jpg" alt="">
				  					<p>国内游</p>
				  				</div>
				  			</div>
				  			<div class="list_div list_div_02">
				  				<div class="list_div_">
				  					<img src="../assets/27.jpg" alt="">
				  					<p>出境游</p>
				  				</div>
				  			</div>
				  			<div class="list_div list_div_03">
				  				<div class="list_div_">
				  					<img src="../assets/28.jpg" alt="">
				  					<p>周边游</p>
				  				</div>
				  			</div>
				  			<div class="list_div list_div_04">
				  				<div class="list_div_">
				  					<img src="../assets/dingz.svg" alt="">
				  					<p>订制</p>
				  				</div>
				  			</div>
				  			<div class="list_div list_div_05">
				  				<div class="list_div_">
				  					<img src="../assets/29.jpg" alt="">
				  					<p>签证</p>
				  				</div>
				  			</div>
				  		</div>
				  		<svg id="paths02" width="375px" height="420px" viewBox="0 0 375 420" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
						    <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
						        <g id="paths02_" transform="translate(0.000000, -2870.000000)" stroke="#62C8F2" stroke-width="4">
						            <g id="Group-21" transform="translate(0.000000, 2867.000000)">
						                <g id="Group-22">
						                    <path d="M379,0 C363.9152,30.6538832 344.575787,87.9211193 228.886162,111.142427 C113.196537,134.363735 -27.7540035,195.730551 65.9664897,225.437712 C159.686983,255.144872 362.415324,286.263683 292.669713,350.331275 C246.172639,393.043003 148.616068,416.599245 0,421" id="Path-5"></path>
						                </g>
						            </g>
						        </g>
						    </g>
						</svg>
			  		</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-6">
			<div class="con">
				<div id="swiper01" class="swiper-container">
	          		<div class="swiper-wrapper">
	            		<div class="swiper-slide">
						  	<div class="list_div list_bg_01">
						  		<div class="list_div_">
							  		<img class="card-img" src="../assets/32.svg" alt="">
							  		<h3>如何开通旅行社？</h3>
							  		<h4>免费开通个人旅行社，共享平台1000款好物！</h4>
						  		</div>
						  	</div>
	            		</div>
	            		<div class="swiper-slide">
						  	<div class="list_div list_bg_02">
						  		<div class="list_div_">
							  		<img class="card-img" src="../assets/33.svg" alt="">
							  		<h3>如何获得收益？</h3>
							  		<h4>可获得20%-60%的利润奖励</h4>
							  		<p>分享商品——好友——购买成功<br/>粉丝、好友——个人旅游平台——购买成功</p>
						  		</div>
						  	</div>
	            		</div>
	            	</div>
	            	<div class="swiper-pagination"></div>
	            </div>
			</div>
		</div>
		<div class="selection selection-7">
			<div class="con">
			  	<div class="cont">
			  		<h2>目标群体</h2>
			  		<div id="swiper02" class="swiper-container">
		          		<div class="swiper-wrapper">
		            		<div class="swiper-slide">
			            		<div class="list_div">
			            			<div class="list_div_">
						  				<div class="list_bg list_bg_01"></div>	
					  					<p>旅行达人</p>
					  				</div>
					  			</div>
		            		</div>
		            		<div class="swiper-slide">
		            			<div class="list_div">
					  				<div class="list_div_">
						  				<div class="list_bg list_bg_02"></div>	
					  					<p>微商群体</p>
					  				</div>
					  			</div>
		            		</div>
		            		<div class="swiper-slide">
		            			<div class="list_div">
					  				<div class="list_div_">
						  				<div class="list_bg list_bg_03"></div>	
					  					<p>上班族</p>
					  				</div>
					  			</div>
		            		</div>
		            		<div class="swiper-slide">
			            		<div class="list_div">
					  				<div class="list_div_">
						  				<div class="list_bg list_bg_04"></div>	
					  					<p>学生党</p>
					  				</div>
					  			</div>
		            		</div>
		            		<div class="swiper-slide">
		            			<div class="list_div">
					  				<div class="list_div_">
						  				<div class="list_bg list_bg_05"></div>	
					  					<p>自由职业者</p>
					  				</div>
					  			</div>
		            		</div>
		            		<div class="swiper-slide">
		            			<div class="list_div">
					  				<div class="list_div_">
						  				<div class="list_bg list_bg_06"></div>	
					  					<p>全职妈妈</p>
					  				</div>
					  			</div>
		            		</div>
		            	</div>
			            <div class="swiper-pagination"></div>
		            </div>
			  	</div>	
			</div>
		</div>
		<div class="selection selection-8">
		  	<div class="con">
				<div class="cont">
					<img class="icon" src="../assets/21.svg" alt="">
					<div class="tit-con">
						<div class="tit-con_">
							<h1 style="margin-bottom: 2vh; font-family: PingFangSC-Regular">免费开通线上旅行社<br/>日赚<strong>¥1000</strong>
							</h1>
							<h2>长按识别小程序码<br/>分享模式立即启动</h2>
						</div>
					</div>
					<img class="code" src="../assets/42.png" alt="">
				</div>
		  	</div>
		</div>
		<app-footer></app-footer>
	</div>
  </div>
</template>

<script>
import '../../static/js/zturn.js'
import Header from './Header'
import Footer from './Footer'
export default {
  name: 'Home',
  data () {
    return {
    	selShow: false
    }
  },
  created() {

  },
  methods: {
    slideDown() {
      let downHeight = document.documentElement.clientHeight || document.body.clientHeight;
      window.scrollTo(0, downHeight);
      this.slideShow = true;
    },
  },
  components: {
    'app-header': Header,
    'app-footer': Footer
  },
  mounted() {

	// 图片轮播
	let zTurn = new zturn({
		id: "zturn",
		opacity: 1,
		width: 18.73,
		Awidth: 51,
		scale: 0.9
	});

	let timer = setInterval(function(){
	    zTurn.next_();
	},2000);

	$('.list-con').hover(function() {
		clearTimeout(timer);
	}, function() {
		timer = setInterval(function(){
		    zTurn.next_();
		},5000);
	});

	let zTurns = new zturn({
		id: "zturns",
		opacity: 1,
		width: 48.73,
		Awidth: 120,
		scale: 0.9
	});

	let timers = setInterval(function(){
	    zTurns.next_();
	},2000);

	let swiper = new Swiper('#swiper01', {
	  loop: 1,
	  autoplay: 3000,
	  autoplayDisableOnInteraction : false,
      slidesPerView: 1,
      spaceBetween: 0,
      speed: 1000,
      releaseOnEdges: true,
      paginationClickable: true,
      pagination: '.swiper-pagination',
    });
	let swiper01 = new Swiper('#swiper02', {
	  loop: 1,
	  autoplay: 3000,
	  autoplayDisableOnInteraction : false,
      slidesPerView: 1,
      spaceBetween: 30,
      speed: 1000,
      releaseOnEdges: true,
      paginationClickable: true,
      pagination: '.swiper-pagination',
    });
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	.video1 {
	    position: relative;
	    left: 0;
	    top: 0;
	    z-index: -1;
	    width: 100%;
	    height: 100%;
	    -o-object-fit: fill;
	    object-fit: fill;
	}
	
	/*selection-1*/
	.selection-1 .con {
		position: absolute;
		left: 0;
		top: 0;
		width: 100%;
		height: 100vh;
		background: rgba(64, 154, 255, 0.25);
	}
	.selection-1 .cont {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 55%;
	}
	.selection-1 .cont .c_tit {
		position: relative;
	}
	.selection-1 .cont .c_tit:after {
		position: absolute;
		left: 8.8vw;
		top: -4.81vh;
		content: '';
		width: 11.61vw;
		height: 4.95vw;
		background: url('../assets/2.svg') center center no-repeat;
		background-size: 100% 100%;
		-webkit-animation: translate 2s  ease-in-out;
    	animation: translate 2s ease-in-out;
	}
	.selection-1 .cont img {
		width: 40.73vw;
	}
	.selection-1 .cont h3 {
		width: 20.42vw;
		height: 2.4vw;
		margin: 3.7vh auto 0;
		border-radius: 100px;
		color: #FFFFFF;
		text-align: center;
		line-height: 2.4vw;
		font-size: 1.3vw;
		font-family: 'PingFangSC-Light';
		background: rgba(0, 0, 0, 0.6);
	}
	/*selection-2*/
	.selection-2 {
		background: url('../assets/11.jpg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-2 .con {
		position: relative;
		height: 100%;
	}
	.selection-2 .cont {
		width: 100%;
	}
	.selection-2 .cont img {
		display: block;
		width: 2.86vw;
		height: 2.86vw;
		margin: 8.33vh auto 1.2vh;
	}
	.selection-2 .cont h1 {
		margin-bottom: 2.22vh;
		color: #000;		
		text-align: center;
		font-size: 2.34vw;
		font-family: 'PingFangSC-Regular';
	}
	.selection-2 .cont p {
		width: 51.98vw;
		margin: 0 auto 2.69vh;
		color: #373737;
		text-align: center;
		line-height: 2.34vw;
		font-size: 1.04vw;
		font-family: 'PingFangSC-Light';
	}
	.selection-2 .path_con {
		position: absolute;
		left: -75vw;
		margin-left: 50vw;
		top: 38.33vh;
		width: 150vw;
		height: 150vw;
		border: 1px dotted #979797;
		border-radius: 50%;
	}
	.selection-2 .pathCons {
		position: relative;
	}
	#plane {
		width: 100%;
	}
	#planes {
		position: absolute;
		left: 0;
		top: -1vw;
		width: 100%;
	}
	#planePath {
		transform: rotate(-90deg);
	}


	/*selection-3*/
	.selection-3 {

	}
	.selection-3 .con {
		position: absolute;
		left: 0;
		top: 0;
		z-index: 22;
	}
	.selection-3 .cont {
		background: rgba(64, 154, 255, 0.25);
	}
	
	.selection-3 .video1 {
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
	}
	.selection-3 .cont {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.selection-3 .left-con {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 54.69vw;
		height: 100vh;
	}
	.selection-3 .left {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 32.19vw;
		height: 28.44vw;
		background: rgba(255, 255, 255, 0.5);
		border-radius: 5px;
	}
	.selection-3 .left_ {
		
	}
	.selection-3 .left-con h3 {
		margin-bottom: 2.7vh;
		color: #000;
		text-align: center;
		font-size: 2.2vw;
		font-family: 'PingFangSC-Regular';
	}
	.selection-3 .tag {
		margin-bottom: 4.67vh;
		text-align: center;
	}
	.selection-3 .tag span {
		display: inline-block;
		width: 10.16vw;
		height: 2.71vw;		
		margin: 0 1.02vw;
		border-radius: 100px;
		color: #5BB8DE;
		text-align: center;
		line-height: 2.71vw;
		font-size: 1.25vw;
		font-family: 'PingFangSC-Regular';
		background: #fff;
		cursor: pointer;
		box-shadow:0px 0px 8px #5BB8DE;
	}
	.selection-3 .tag_02 span {
		width: 6.77vw;
		height: 2.14vw;
		margin: 0 0.44vw;
		line-height: 2.14vw;
	}
	.selection-3 .tag_02 {
		margin-bottom: 0;
	}
	.selection-3 .left-con img {
		width: 23.75vw;
	}
	.selection-3 .right {
		overflow: hidden;
		position: relative;
		width: 45.31vw;
		height: 100vh;
	}
	.selection-3 .right img {
		position: absolute;
		top: 9.44vh;
		right: 5.83vw;
		width: 5.83vw;
	}
	.selection-3 .right h1 {
		position: absolute;
		left: 6.09vw;
		bottom: 7.4vh;
		color: #FFFFFF;
		font-size: 2.86vw;
		font-family: 'PingFangSC-Semibold';
	}
	.selection-3 .right h1:after {
		position: absolute;
		left: 0;
		top: -4.44vh;
		content: '';
		width: 4.17vw;
		height: 0.26vw;
		background: #5BB8DE;
	}
	.selection-3 .right_bg {
		position: absolute;
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
	}

	/*selection-4*/
	.selection-4 {
		background: url('../assets/15.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-4 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100%;
	}
	.selection-4 .cont  {
		position: relative;
		width: 100%;
	}
	.selection-4 h2 {
		position: relative;
		color: #FFFFFF;		
		text-align: center;
		text-shadow: 0 2px 4px rgba(0,0,0,0.76);
		font-family: 'PingFangSC-Regular';
		font-size: 2.34vw;
	}
	.selection-4 h2:after {
		position: absolute;
		left: 0;
		right: 0;
		bottom: -3.74vh;
		margin: 0 auto;
		content: '';
		width: 1.46vw;
		height: 1.46vw;
		background: url('../assets/21.svg') center center no-repeat;
		background-size: 100% 100%;
	}

	.selection-4 .list-con {
		position: relative;
		width: 100%;
		height: 32.24vw;
		margin-top: 8.33vh;
	}
	.selection-4 .list-con .list_div {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.selection-4 .list-con img {
		width: 19.22vw;
		height: 32.24vw;
	}

	.pictureSlider {
	    height: 59.07vh;
	}
	.selection-4 .poster-list {
		width: 100%;
		height: 50vh;
	}
	.poster-item {
		position: relative;
		width: 19.22vw;
		transition: all 0.5s;
		-moz-transition: all 0.5s;
		-webkit-transition: all 0.5s;
		-o-transition: all 0.5s;
		cursor: pointer;
	}

	/*selection-5*/
	.selection-5 {
		background: url('../assets/22.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-5 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100%;
	}
	.selection-5 h2 {
		position: relative;
		color: #FFFFFF;		
		text-align: center;
		text-shadow: 0 2px 4px rgba(0,0,0,0.76);
		font-family: 'PingFangSC-Regular';
		font-size: 2.34vw;
	}
	.selection-5 h2:after {
		position: absolute;
		left: 0;
		right: 0;
		bottom: -3.74vh;
		margin: 0 auto;
		content: '';
		width: 1.46vw;
		height: 1.46vw;
		background: url('../assets/21.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-5 #pathsCon {
		display: block;
		width: 100vw;
		height: auto;
	}
	.selection-5 #paths {
		width: 100%;

	}
	.selection-5 path {
	  animation: dash 4s linear;
	}
	.selection-5 .conts {
		position: relative;
	}

	.selection-5 .floatcon {
		position: absolute;
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
	}
	.selection-5 .list_div {
		position: absolute;
		display: flex;
		justify-content: center;
		align-items: flex-start;
		width: 10vw;
		height: 13.54vw;
		background: url('../assets/25.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-5 .list_div_ {
		margin-top: 1.2vw;
	}
	.selection-5 .list_div:after {
		content: '';
		position: absolute;
		left: 0;
		right: 0;
		bottom: -3.48vw;
		margin: auto;
		width: 2.71vw;
		height: 2.71vw;
		background: url('../assets/24.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-5 .list_div img {
		width: 6.04vw;
		height: 6.04vw;
	}
	.selection-5 .list_div p {
		color: #5BB8DE;
		text-align: center;
		font-size: 1.56vw;
		font-family: 'PingFangSC-Medium';
	}

	.selection-5 .list_div_01 {
		left: 11.51vw;
		bottom: 8.69vw;
		-webkit-animation: opac 2.2s infinite ease-in-out;
    	animation: opac 2.2s infinite ease-in-out;
    	-webkit-animation-delay: 4s;
    	animation-delay: 4s;
    	opacity: 0;
	}
	.selection-5 .list_div_02 {
		left: 26.51vw;
    	bottom: 10.5vw;
		-webkit-animation: opac 2.2s infinite;
    	animation: opac 2.2s infinite;
    	-webkit-animation-delay: 5s;
    	animation-delay: 5s;
    	opacity: 0;
	}
	.selection-5 .list_div_03 {
		left: 47.13vw;
        bottom: 14vw;
		-webkit-animation: opac 2.2s infinite;
    	animation: opac 2.2s infinite;
    	-webkit-animation-delay: 6s;
    	animation-delay: 6s;
    	opacity: 0;
	}
	.selection-5 .list_div_04 {
		left: 63.13vw;
        bottom: 13.5vw;
		-webkit-animation: opac 2.2s infinite;
    	animation: opac 2.2s infinite;
    	-webkit-animation-delay: 7s;
    	animation-delay: 7s;
    	opacity: 0;
	}
	.selection-5 .list_div_05 {
		left: 80.13vw;
		bottom: 8.5vw;
		-webkit-animation: opac 2.2s infinite;
    	animation: opac 2.2s infinite;
    	-webkit-animation-delay: 8s;
    	animation-delay: 8s;
    	opacity: 0;
	}

	@keyframes dash {
		0% {
			stroke-dasharray: 5000;
	  		stroke-dashoffset: 5000;
		}
	  	100% {
	    	stroke-dashoffset: 0;
	  	}
	}

	/*selection-6*/
	.selection-6 {

	}
	.selection-6 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100%;
	}
	.selection-6 .list_div img {
		display: block;
		width: 4.69vw;
		height: 4.69vw;
		margin: 0 auto 7.31vh;
	}
	.selection-6 .list_bg_01 h3, .selection-6 .list_bg_01 h4 {
		text-indent: 1em;
	}
    .selection-6 .list_bg_02 h4 {
		text-indent: -1em;
	}

	.selection-6 .list_div h3 {
		margin-bottom: 2.5vh;		
		text-align: center;
		font-size: 2.34vw;
		font-family: 'PingFangSC-Regular';
		text-shadow: 0 2px 4px rgba(0,0,0,0.76);
	}
	.selection-6 .list_div h4 {
		margin-bottom: 2.5vh;
		text-align: center;
		font-size: 1.3vw;
		font-family: 'PingFangSC-Light';
		text-shadow: 0 2px 4px rgba(0,0,0,0.76);
	}
	.selection-6 .list_div p {
		padding-left: -1em;
		text-align: center;
		font-size: 0.8vw;
		font-family: 'PingFangSC-Light';
		opacity: 0;
		text-shadow: 0 2px 4px rgba(0,0,0,0.76);
	}
	.selection-6 .list_bg_01 {
		background: url('../assets/30.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-6 .list_bg_02 {
		background: url('../assets/31.jpg') center center no-repeat;
		background-size: cover;
	}

	.selection-6 .list_div {
	    flex: 1;
	    height: 100%;
	    position: relative;
	    overflow: hidden;
	    cursor: pointer;
	}
  	.selection-6 .list_bg {
	    position: absolute;
	    width: 8vw;
	    height: 8vw;
	    border-radius: 100%;
	    overflow: hidden;
	    margin: auto;
	    -webkit-box-sizing: content-box;
	    box-sizing: content-box;
	    background-size: cover;
	    background-origin: border-box;
	    -webkit-transition: all .6s;
	    transition: all .6s;
	}
	.selection-6 .list_bg_01 .list_bg {
	    top: -87.5vw;
    	left: -78.8vw;
	    border: 100vw solid #f5f5f5;
	}
	.selection-6 .list_bg_02 .list_bg {
	    top: -87.5vw;
    	left: -79.5vw;
    	border: 100vw solid #fff;
	}
	
  	.selection-6 .list_div_ {
	    position: absolute;
	    z-index: 100;
	    width: 80%;
	    height: 100%;
	    top: 14.2vw;
	    left: 0;
	    right: 0;
	    margin: 0 auto;
	    -webkit-transition: all .6s;
	    transition: all .6s;
	}
	.selection-6 .list_div:hover p {
		opacity: 1;
	}
	
	/*selection-7*/
	.selection-7 {
		background: url('../assets/34.jpg') center center  no-repeat;
		background-size: cover;
	}
	.selection-7 .con {
		display: flex;
		align-items: center;
		justify-content: center;
		height: 100%;
	}
	.selection-7 .cont {
		width: 80%;
	}
	.selection-7 h2 {
		position: relative;
		margin-bottom: 8.43vh;
		color: #FFFFFF;
		text-shadow: 0 2px 4px rgba(0,0,0,0.76);
		font-size: 2.34vw;
		font-family: 'PingFangSC-Regular';
	}
	.selection-7 h2:after {
		position: absolute;
		right: 2vw;
		bottom: 30%;
		margin: 0 auto;
		content: '';
		width: 1.46vw;
		height: 1.46vw;
		background: url('../assets/21.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-7 .list_con {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.selection-7 .list_div {
		overflow: hidden;
		width: 13.13vw;
		height: 23.44vw;
		margin-right: 0.42vw;
		background: #fafafa;
		border-radius: 0.42vw;
		box-shadow: 0 0 50px 0 rgba(0,0,0,.3);
		cursor: pointer;
		-webkit-transition: all .6s;
	    transition: all .6s;
	}
	.selection-7 .list_bg {
		width: 100%;
		height: 18.02vw;
	}
	.selection-7 p {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 5.42vw;
		color: #373737;
		text-align: center;
		font-size: 1.3vw;
		font-family: 'PingFangSC-Light';
	}
	.selection-7 .list_bg_01 {
		background: url('../assets/35.jpg') center center no-repeat;
		background-size: 100% 100%;	
	}
	.selection-7 .list_bg_02 {
		background: url('../assets/36.jpg') center center no-repeat;
		background-size: 100% 100%;	
	}
	.selection-7 .list_bg_03 {
		background: url('../assets/37.jpg') center center no-repeat;
		background-size: 100% 100%;	
	}
	.selection-7 .list_bg_04 {
		background: url('../assets/38.jpg') center center no-repeat;
		background-size: 100% 100%;	
	}
	.selection-7 .list_bg_05 {
		background: url('../assets/39.jpg') center center no-repeat;
		background-size: 100% 100%;	
	}
	.selection-7 .list_bg_06 {
		background: url('../assets/40.jpg') center center no-repeat;
		background-size: 100% 100%;	
	}
	
	
	/*selection-8*/
	.selection-8 {

	}
	.selection-8 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 79.07vh;
		background: url('../assets/41.jpg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-8 .cont {

	}
	.selection-8 .tit-con {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 46.35vw;
		height: 13.18vw;
		margin-bottom: 4.63vh;
		border-radius: 15px;
		background: rgba(68, 177, 221, 0.6);
	}
	.selection-8 .cont h1 {
		margin: 0 auto;
		color: #FFFFFF;
		text-align: center;
		line-height: 3.91vw;
		font-size: 2.34vw;
		font-family: 'PingFangSC-Light';
	}
	.selection-8 .cont strong {
		color: #fff;
		line-height: 3.91vw;
		font-size: 2.86vw;
		font-family: 'PingFangSC-Semibold';
	}
	.selection-8 .cont .code {	
		display: block;	
		width: 12.45vw;
		height: 12.45vw;
		margin: 0 auto;
	}

	.selection-8 .icon {
		display: block;
		width: 1.46vw;
		height: 1.3vw;
		margin: 0 auto 5.83vh;
	}

	/*向下效果*/
	@-webkit-keyframes translate {
	    0% {
	        -webkit-transform: translateY(100px) translateX(-300px);
	        -moz-transform: translateY(100px) translateX(-300px);
	        -ms-transform: translateY(100px) translateX(-300px);
	        -o-transform: translateY(100px) translateX(-300px);
	    }
	    100% {
	        -webkit-transform: translateY(0px) translateX(0px);
	        -moz-transform: translateY(0px) translateX(0px);
	        -ms-transform: translateY(0px) translateX(0px);
	        -o-transform: translateY(0px) translateX(0px);
	    }
	}
  	@keyframes translate {
	    0% {
	        -webkit-transform: translateY(100px) translateX(-300px);
	        -moz-transform: translateY(100px) translateX(-300px);
	        -ms-transform: translateY(100px) translateX(-300px);
	        -o-transform: translateY(100px) translateX(-300px);
	    }
	    100% {
	        -webkit-transform: translateY(0px) translateX(0px);
	        -moz-transform: translateY(0px) translateX(0px);
	        -ms-transform: translateY(0px) translateX(0px);
	        -o-transform: translateY(0px) translateX(0px);
	    }
	}

	@media screen and (max-width: 750px) {
		.mob {
			display: block;
		}
		.video1 {
		    width: 200%;
		}

		/*selection-1*/
		.selection-1 .cont {
			height: 70%;
		}
		.selection-1 .cont .c_tit:after {
			position: absolute;
			left: 14.8vw;
    		top: -6.81vh;
			content: '';
			width: 29.47vw;
			height: 15.33vw;
		}
		.selection-1 .cont img {
			width: 86.67vw;
		}
		.selection-1 .cont h3 {
			width: 55.2vw;
			height: 6.67vw;
			margin: 4.65vh auto 0;
			line-height: 6.4vw;
			font-size: 4.27vw;
		}
		
		/*selection-2*/
		.selection-2 {
			background: url('../assets/003.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-2 .con {
			position: relative;
			height: 100%;
		}
		.selection-2 .con_bg {
			position: absolute;
			left: 0;
			bottom: 0;
			width: 100%;
			height: 58.61vh;
			background: url('../assets/003.png') center center no-repeat;
			background-size: 100% 100%;
		}
		.selection-2 .cont {
			width: 100%;
			/*height: 100%;*/
		}
		.selection-2 .cont img {
			width: 7.47vw;
			height: 7.47vw;
			margin: 8.33vh auto 2.1vh;
		}
		.selection-2 .cont h1 {
			margin-bottom: 3.6vh;
			font-size: 6.67vw;
		}
		.selection-2 .cont p {
			width: 85%;
			margin: 0 auto 9.69vh;
			text-align: left;
			line-height: 8vw;
			font-size: 3.73vw;
		}
		.selection-2 .cont p strong {
			color: #5BB8DE;
			font-size: 4.2vw;
			font-family: 'PingFangSC-Medium';
		}
		.selection-2 .path_con {
			position: absolute;
			left: -75vw;
			margin-left: 50vw;
			top: 38.33vh;
			width: 150vw;
			height: 150vw;
			border: 1px dotted #979797;
			border-radius: 50%;
		}
		#plane {
			width: 100%;
			height: auto;
		}
		#planes {
			top: -10.5vw;
			width: 100%;
			height: 15vh;
		}
		#planePath {
		    -webkit-transform: rotate(-90deg);
		    transform: rotate(-90deg);
		}

		/*selection-3*/
		.selection-3 .con {
			width: 100%;
			height: 100vh;
		}
		.selection-3 .video1 {
			left: -50%;
			width: 200%;
		}
		.selection-3 .cont {
			width: 100%;
			height: 100%;
		}
		.selection-3 .left-con {
			width: 85.07vw;
			height: 47.38vh;
			margin: 0 auto 32vh;
			border-radius: 5px;
			background: rgba(255,255,255,0.42);
		}
		.selection-3 .left {
			display: block;
			width: 100%;
			height: auto;
			background: transparent;
		}
		.selection-3 .left-con h3 {
			margin-bottom: 3vh;
			text-align: center;
			font-size: 6.13vw;
		}
		.selection-3 .left-con img {
			display: block;
			width: 57.07vw;
			margin: 0 auto;
		}
		.selection-3 .tag {
			text-align: center;
		}
		.selection-3 .tag span {
			line-height: 6.4vw;
			font-size: 3.73vw;
		}
		.selection-3 .tag_01 span {
			width: 25.07vw;
			height: 6.4vw;	
			margin: 0 2.94vw;
		}
		.selection-3 .tag_02 span {
			width: 19.47vw;
			height: 6.4vw;
			margin-right: 1.77vw;
		}
		.selection-3 .right {
			position: absolute;
			left: 0;
			top: 0;
			width: 100vw;
			height: 100vh;
			z-index: -1;
		}
		.selection-3 .right img {
			top: 0;
			left: 0;
			width: 100vw;
			height: 100vh;
		}
		.selection-3 .right_bg {
			position: absolute;
			left: 0;
			top: 0;
			width: 100%;
			height: 100%;
		}

		/*selection-4*/
		.selection-4 {
			background: url('../assets/009.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-4 .con {
			height: 40%;
		}
		.selection-4 .cont  {
			position: relative;
			width: 100%;
		}
		.selection-4 h2 {
			font-size: 6.67vw;
		}
		.selection-4 h2:after {
			bottom: -6.74vh;
			width: 7.47vw;
			height: 6.67vw;
		}
		.selection-4 .list-con {
			position: absolute;
			left: -25%;
			top: 0;
			width: 150%;
			height: 75.24vw;
			margin-top: 19.44vh;
		}
		.selection-4 .list-con .list_div {
			display: flex;
			justify-content: center;
			align-items: center;
			width: 100%;
		}
		.selection-4 .list-con img {
			width: 48.22vw;
    		height: 75.24vw;
		}

		.pictureSlider {
		    height: 59.07vh;
		}
		.selection-4 .poster-list {
			width: 100%;
			height: 50vh;
		}
		.poster-item {
			position: relative;
			width: 48.22vw;
		}

		/*selection-5*/
		.selection-5 {
			background: url('../assets/010.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-5 .con {
			height: 100%;
		}
		.selection-5 h2 {
			margin-bottom: 12vh;
			font-size: 6.67vw;
		}
		.selection-5 h2:after {
			position: absolute;
			left: 0;
			right: 0;
			bottom: -6.74vh;
			width: 7.47vw;
			height: 6.67vw;
		}
		.selection-5 #paths02 {
			display: block;
			width: 100vw;
			height: auto;
		}
		.selection-5 #paths02_ {
			width: 100%;

		}
		.selection-5 path {
		  animation: dash 4s linear;
		}
		.selection-5 .conts {
			position: relative;
		}

		.selection-5 .floatcon {
			position: absolute;
			left: 0;
			top: 0;
			width: 100%;
			height: 100%;
		}
		.selection-5 .list_div {
			width: 25.33vw;
			height: 34.13vw;
		}
		.selection-5 .list_div_ {
			margin-top: 2.7vw;
		}
		.selection-5 .list_div:after {
			bottom: -10.48vw;
			margin: auto;
			width: 8.53vw;
			height: 8.53vw;
			background: url('../assets/24.svg') center center no-repeat;
			background-size: 100% 100%;
		}
		.selection-5 .list_div img {
			display: block;
			width: 12vw;
			height: 12vw;
			margin: 0 auto;
		}
		.selection-5 .list_div p {
			font-size: 3.73vw;
		}

		.selection-5 .list_div_01 {
			left: 11.51vw;
			bottom: 77.69vw;
			-webkit-animation: opac 2.2s infinite;
	    	animation: opac 2.2s infinite;
	    	-webkit-animation-delay: 3s;
	    	animation-delay: 3s;
	    	opacity: 0;
		}
		.selection-5 .list_div_02 {
			left: 65.51vw;
    		bottom: 94.5vw;
			-webkit-animation: opac 2.2s infinite;
	    	animation: opac 2.2s infinite;
	    	-webkit-animation-delay: 2s;
	    	animation-delay: 2s;
	    	opacity: 0;
		}
		.selection-5 .list_div_03 {
			left: 38.13vw;
    		bottom: 49.5vw;
			-webkit-animation: opac 2.2s infinite;
	    	animation: opac 2.2s infinite;
	    	-webkit-animation-delay: 4s;
	    	animation-delay: 4s;
	    	opacity: 0;
		}
		.selection-5 .list_div_04 {
			left: 64.13vw;
    		bottom: 23.5vw;
			-webkit-animation: opac 2.2s infinite;
	    	animation: opac 2.2s infinite;
	    	-webkit-animation-delay: 5s;
	    	animation-delay: 5s;
	    	opacity: 0;
		}
		.selection-5 .list_div_05 {
			left: 20.13vw;
    		bottom: 9.5vw;
			-webkit-animation: opac 2.2s infinite;
	    	animation: opac 2.2s infinite;
	    	-webkit-animation-delay: 6s;
	    	animation-delay: 6s;
	    	opacity: 0;
		}

		@keyframes dash {
			0% {
				stroke-dasharray: 5000;
		  		stroke-dashoffset: 5000;
			}
		  	100% {
		    	stroke-dashoffset: 0;
		  	}
		}

		/*selection-6*/
		.selection-6 .con {
			height: 100%;
		}
		
		.selection-6 .list_div img {
			display: block;
			width: 18.4vw;
			height: 16.53vw;
			margin: 0 auto 8.1vh;
		}

		.selection-6 .list_div h3 {
			margin-bottom: 2.25vh;	
			color: #fff;	
			text-indent: 1em;
			font-size: 6.67vw;
		}
		.selection-6 .list_div h4 {
			margin-bottom: 2.25vh;
			color: #fff;
			text-indent: 1em;
			font-size: 3.73vw;
			font-family: 'PingFangSC-Regular';
		}
		.selection-6 .list_div p {
			color: #fff;
			padding-left: 1em;
			font-size: 3.2vw;
			font-family: 'PingFangSC-Regular';
			opacity: 1;
		}
		.selection-6 .list_bg_01 {
			background: url('../assets/013.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-6 .list_bg_02 {
			background: url('../assets/014.jpg') center center no-repeat;
			background-size: cover;
		}

		#swiper01 {
			width: 100vw;
			height: 100vh;
		}
		.selection-6 .list_div {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 85.01vh;
		}
		

	  	.selection-6 .list_div_ {
		    position: static;
		    height: 35vh;
		}
		
		/*selection-7*/
		.selection-7 {
			background: url('../assets/18.jpg') center center  no-repeat;
			background-size: cover;
		}
		.selection-7 .con {
			height: 100%;
		}
		.selection-7 .cont {
			width: 100%;
		}
		.selection-7 h2 {
			margin-bottom: 9.15vh;
			text-align: center;
			font-size: 6.67vw;
		}
		.selection-7 h2:after {
			position: absolute;
			right: 0;
			left: 0;
			bottom: -6.25vh;
			margin: 0 auto;
			width: 7.47vw;
			height: 7.47vw;
			background: url('../assets/21.svg') center center no-repeat;
			background-size: 100% 100%;
		}
		.selection-7 .list_div {
			overflow: hidden;
			width: 67.2vw;
			height: 64.32vh;
			margin: 0 auto;
			background: #fafafa;
			border-radius: 2.13vw;
			box-shadow: 0 0 50px 0 rgba(0,0,0,.3);
		}
		.selection-7 .list_bg {
			width: 100%;
			height: 51.87vh;
		}
		.selection-7 p {
			height: 12.44vh;
			font-size: 6.67vw;
		}
		.selection-7 .list_bg_01 {
			background: url('../assets/35.jpg') center center no-repeat;
			background-size: 100% 100%;	
		}
		.selection-7 .list_bg_02 {
			background: url('../assets/36.jpg') center center no-repeat;
			background-size: 100% 100%;	
		}
		.selection-7 .list_bg_03 {
			background: url('../assets/37.jpg') center center no-repeat;
			background-size: 100% 100%;	
		}
		.selection-7 .list_bg_04 {
			background: url('../assets/38.jpg') center center no-repeat;
			background-size: 100% 100%;	
		}
		.selection-7 .list_bg_05 {
			background: url('../assets/39.jpg') center center no-repeat;
			background-size: 100% 100%;	
		}
		.selection-7 .list_bg_06 {
			background: url('../assets/40.jpg') center center no-repeat;
			background-size: 100% 100%;	
		}
		#swiper02 {
			width: 100%;
			height: 70vh;
		}

		/*selection-8*/
		.selection-8 {

		}
		.selection-8 .con {
			height: 100vh;
			background: url('../assets/19.jpg') center center no-repeat;
			background-size: 100% 100%;
		}
		.selection-8 .cont {
			display: block;
			width: 80%;
			margin: 0 auto;
		}
		.selection-8 .icon {
			display: block;
			width: 7.47vw;
			height: 6.67vw;
			margin: 0 auto 4.63vh;
		}
		.selection-8 .tit-con {
			width: 76.53vw;
			height: 51.47vw;
			margin: 0 auto;
		}
		.selection-8 .cont h1 {
			width: 100%;
			text-align: center;
			line-height: 9.33vw;
			font-size: 6.67vw;
		}
		.selection-8 .cont h2 {
			color: #fff;
			text-align: center;
			line-height: 6.33vw;
			font-size: 4.67vw;
			font-family: 'PingFangSC-Regular';
		}
		.selection-8 .cont strong {
			line-height: 9.33vw;
			font-size: 6.67vw;
		}
		.selection-8 .cont .code {
			display: block;		
			width: 40vw;
			height: 40vw;
			margin: 6.2vh auto 0;
		}

	}

	@media screen and (min-width: 751px) {
		.selection-6 .list_div:hover .list_bg {
		    -webkit-transform: scale(30);
		    transform: scale(30);
		    -webkit-transition: all .6s;
		    transition: all .6s;
		}
		.selection-6 .list_div:hover {
			color: #fff;
		}

		.selection-7 .list_div:hover {
			-webkit-transform: scale(1.1);
		    transform: scale(1.1);
			-webkit-transition: all .6s;
		    transition: all .6s;
		}
	}
</style>
