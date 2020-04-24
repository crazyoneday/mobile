<template>
	<vue-editor v-model="content" />
</template>

<script>

import { VueEditor } from "vue2-editor";


export default {
  name: 'HelloWorld',
  components: { VueEditor },
  data () {
    return {
	 content: "<h1>Some initial content</h1>",
      msg: 'Welcome to Your Vue.js App'
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
