<template >
	<div class="liuContent">
		<div class="content-right">
			<div class="content-right-top">
			    <el-row class="row">
					<span class="p1-name">刘医生</span>
					<el-radio-button>出诊</el-radio-button>
					<el-time-picker is-range v-model="time" placeholder="选择时间范围">
					</el-time-picker>	  							 
				</el-row>	
			</div>
			<div class="content-right-bottom">
				<img src="../../assets/40.png" class="bells" > 
				<p>暂无预约信息</p>		
			</div>
		</div>
	</div>	
</template>

<script>
// import "../../assets/css/style1.css"
	//npm i element-ui -S 等同于
	//npm install element-ui --save
	export default {
	  name: 'home',
	  data: function () {
	    return {
	    	time:''
	    }
	  }
	}
</script>

<style>
	.liuContent .content-right .content-right-top{
		margin-top:1.25%;
	}
	.liuContent .content-right .content-right-top .row{
		line-height:50px;
	}
	.liuContent .content-right .content-right-bottom{
		padding-top: 2%;
	}
	.liuContent .content-right .content-right-bottom .bells{
		margin-left: 40%;
		margin-top: 16%;
	}
	.liuContent .content-right .content-right-bottom p{
		margin-left: 45%;
		opacity: 0.6;
	}
</style>