<template>
  <div class="hello">
	<template>
	123131
	  
	</template>
  </div>
</template>

<script>
import Vue from 'vue'
import { Button } from 'vant'
Vue.use(Button)

import { VueEditor } from "vue2-editor";
import {  Quill } from "vue2-editor";

export default {
  name: 'VueEditor',
  components: { VueEditor },

  data () {
  content: "<h1>Some initial content</h1>";
    return {
      msg: 'product'
    }
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
