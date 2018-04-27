
<template>
  <div id="app">
    <inhead></inhead>
    <Tab></Tab>
    <keep-alive>
    	<router-view></router-view>
    </keep-alive>
  </div>
</template>

<script>
	import inhead from 'components/inhead/inhead'
	import Tab from 'components/tab/tab'
	export default {
	  components: {
	  	inhead,
	  	Tab
	  }
	}


</script>

<style scoped lang="stylus" rel="stylesheet/stylus">

</style>
