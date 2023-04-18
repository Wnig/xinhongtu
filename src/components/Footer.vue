<template>
  <footer>
  	<div class="pc">
	  	<div class="footer">
	  		<h1>厦门欣宏途网络科技有限公司</h1>
	  		<h4>地址：中国-福建省厦门市思明区观音山国际商务营运中心18号楼4层<span></span>咨询热线：189-0604-3830</h4>
	  		<p>ICP备案号：闽ICP备18009115号-1</p>
	  	</div>
  	</div>
  	<div class="mob">
  		<h1>厦门欣宏途网络科技有限公司</h1>
  		<h4>地址：中国厦门市思明区观音山国际商务营运中心18号楼4层<br/>咨询热线：189-0604-3830</h4>
  		<p>ICP备案号：闽ICP备18009115号-1</p>
  	</div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	footer {
		display: flex;
		justify-content: center;
		align-items: center;
		text-align: center;
		height: 20.93vh;
		background: #FFFFFF;
	}
	h1 {
		margin-bottom: 1.39vh;
		color: #4D4D4D;
		text-align: center;
		font-size: 1.3vw;
		font-family: 'PingFangSC-Light';
	}
	h4 {
		margin-bottom: 3.52vh;
		color: #4D4D4D;
		text-align: center;
		font-size: 0.83vw;
		font-family: 'PingFangSC-Light';
	}
	h4 span {
		display: inline-block;
		width: 3vw;
		text-align: center;
	}
	p {
		color: #C6C6C6;
		font-size: 0.73vw;
		font-family: 'PingFangSC-Light';
	}
	.mob {
		display: none;
	}

	@media screen and (max-width: 750px) {
		.mob {
	      	display: block;
	    }

		footer {
			height: 28.34vh;
		}

		h1 {
			color: #000000;
			font-family: 'PingFangSC-Medium';
			font-size: 4.8vw;
		}

		h4 {
			margin-bottom: 1.8vh;
			color: #7E7E7E;
			line-height: 5.33vw;
			font-size: 3.2vw;
			font-family: 'PingFangSC-Light';
		}
		p {
			color: #C6C6C6;
			font-size: 3.2vw;
			font-family: 'PingFangSC-Light';
		}
	}

</style>
