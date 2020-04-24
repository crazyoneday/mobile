<template>
 
 
  <div class="g-fullPage">
            <div class="f-pageFirst">
			 <router-link to="/demose"><h1 id='index_h1'>DEMOSE</h1></router-link>
				
				<img id='myimg' src='../img/index.png'>
			</div>
            <div class="f-pageFirst">
				<h1 id='index_h2'>DEMOSE</h1>
				<img id='myimg2' style='width:100%' src='../img/about.png'>
				<p class='about_p'> 佛山市狄姆斯五金制品有限公司，是一家专业从事制造各类楼梯，栏杆生产厂家。为数不多采用ERP管理系统的楼梯，栏杆制造企业！      其中狄姆斯旋转楼梯，不锈钢栏杆，不锈钢楼梯扶手及护栏配件等特色产品现已出口国外多个国家，受到了各国用户的喜爱</p>
			</div>
            <div class="f-pageFirst"><h1 id='index_h3'>不锈钢楼梯</h1>
				<img class="f-pageFirstimg" src='../img/lg1.jpg'>
			</div>
			<div class="f-pageFirst">4</div>
			<div class="f-pageFirst">5</div>
			<div class="f-pageFirst">6</div>
			
   </div>
 
</template>

<script>
import Vue from 'vue';


import { Swipe, SwipeItem } from 'mint-ui';

Vue.component(Swipe.name, Swipe);
Vue.component(SwipeItem.name, SwipeItem);



import {fullPage} from '../js/full_page.js'
import "../css/common.css";
import "../css/index.css";


export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  mounted () {
	   fullPage("g-fullPage", "f-pageFirst",5);
	}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
