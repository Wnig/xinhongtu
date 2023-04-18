<template>
  	<header>
	  	<div class="pc">
		    <div class="cont">
				<a class="logo" @click="jump" ><img src="../assets/1.svg" alt=""></a>
			  	<nav>
			  		<ul>
						<!-- <li v-for="(navs, index) in navData" v-bind:class="{'btn_sel': index == num}" @click="selMenus(index)">
			              <router-link :to="navs.links">{{navs.tit}}</router-link>
			            </li> -->
			            <li class="backstage">
			              <a href="" target="_blank">后台登录</a>
			            </li>
			  		</ul>
			  	</nav>
		  	</div>
	  	</div>
	  	<div class="mob">
	  		<div class="cont">
				<a class="logo" @click="jump" ><img src="../assets/1.svg" alt=""></a>
				<div class="nav-btn-con">
					<div @click="isShow" class="nav-btn">
						<img src="../assets/002.svg" alt="">
					</div>
				</div>	
				<transition name='fade'>
					<div class="nav" v-show="selShow" @click="isShow">
						<transition name='slide'>
						  	<nav v-if="selShow">
						  		<ul>
									<li v-for="(navs, index) in navData" v-bind:class="{'btn_sel': index == num}" @click="selMenus(index)">
						              <router-link :to="navs.links">{{navs.tit}}</router-link>
						            </li>
						            <li>
						              <a href="">后台登录</a>
						            </li>
						  		</ul>
						  		<div class="hot">
						            <p>咨询热线</p>
						            <h2>189-0604-3830</h2>
						        </div>
						  	</nav>
					  	</transition>
					</div>
				</transition>
		  	</div>
	  	</div>
    </header>
</template>

<script>
let storage = window.sessionStorage;
export default {
  name: 'Header',
  data () {
    return {
    	navData: [
    		{tit: '首页', links:'/'},
        ],
      	num: '',
      	selShow: false
    }
  },
  created: function() {
    if(storage['selNumxinhongtu']) {
      this.num = storage['selNumxinhongtu'];
    } else {
      this.num = 0;
    };
  },
  methods: {
    selMenus(index) {
      storage['selNumxinhongtu'] = index;
      this.selShow = false;
    },
    isShow() {
      //点击：左侧菜单栏 收起-展开
      this.selShow = ! this.selShow;
    },
    jump() {
      storage['selNumxinhongtu'] = 0;
      this.selShow = false;
      this.$router.push({path: '/'});
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	header {
		display: flex;
		justify-content: center;
		height: 10.36vw;
	}
	.pc {
		display: flex;
		width: 88%;
	}
	.cont {
		display: inline-flex;
		align-items: center;
		width: 100%;
	}
	.logo {
		width: 12.86vw;
		cursor: pointer;
	}
	.logo img {
		display: block;
		width: 100%;
	}
	nav {
		flex: 1;
	}
	nav ul {
		display: flex;
		justify-content: flex-end;
		align-items: center;
	}

	nav li a {
		color: #FFFFFF;
		text-align: center;
		font-family: 'PingFangSC-Light';
		font-size: 1.3vw;
	}
	nav a {
		display: block;
		line-height: 2.4vw;
		cursor: pointer;
	}
	nav .backstage {
		width: 8.91vw;
		height: 2.4vw;
		border: 1px solid #FFFFFF;
		border-radius: 100px;
	}
	@media screen and (max-width: 750px) {
		.pc {
			display: none;
		}
		.mob {
			display: flex;
			width: 85%;
		}
		header {
			height: 18.36vw;
		}
		.cont {
			display: inline-flex;
			align-items: center;
			width: 100%;
		}
		.logo {
			width: 38.95vw;
			cursor: pointer;
		}
		.nav-btn-con {
			width: 70%;
		}
		.nav-btn-con .nav-btn {
			display: flex;
			justify-content: flex-end;
			align-items: center;
			float: right;
			width: 22.67vw;
			height: 9.07vw;
		}
		.nav-btn-con .nav-btn img {
			display: block;
			width: 8.27vw;
			height: 6.13vw;
		}
		.nav {
			position: fixed;
			left: 0;
			top: 0;
			width: 100%;
			height: 100vh;
			background: rgba(0, 0, 0, 0.65);
			z-index: 9999;
			opacity: 1;
		}
		.fade-enter-active, .fade-leave-active {
		    transition: all .3s
		}

		.fade-enter, .fade-leave-to {
		    opacity: 0;
		}
		nav {
			width: 66.93vw;
			height: 100vh;
			background: #fff;
			transform: translate3d(0, 0, 0);
		}
		.slide-enter-active, .slide-leave-active {
		    transition: all .3s
		}

		.slide-enter, .slide-leave-to {
		    transform: translate3d(-100%, 0, 0);
		}
		nav ul {
			display: block;
			padding-top: 14.33vh;
			padding-left: 9.07vw;
		}
		nav li {
			margin-bottom: 6.5vh;
		}
		nav p {
	      margin-bottom: 1.05vh;
	      color: #797979;
	      font-size: 3.2vw;
	    }
	    nav h2 {
	      color: #000000;
	      line-height: 6.67vw;
	      font-size: 6.67vw;
	      font-family: 'PingFangSC-Semibold';
	    }
	    nav .hot {
	      position: absolute;
	      left: 9.2vw;
	      bottom: 7.95vh;
	    }
	    nav li a {
			color: #000000;
			text-align: left;
	    	line-height: 7.33vw;
			font-size: 5.33vw;
			font-family: 'PingFangSC-Light';
		}
		nav .btn_sel a {
			color: #5BB8DE;
			font-size: 6.67vw;
			font-family: 'PingFangSC-Semibold';
		}

	}

	@media screen and (min-width: 751px) {
	}
</style>
