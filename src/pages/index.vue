<template>
	<div class="indexPage">
		<v-chooser :selections="fruitList"></v-chooser>
	</div>

</template>

<script>
import VChooser from '../components/base/chooser/chooser'	
export default {
	components:{
		VChooser
	},
	data(){
      return {
      	fruitList:[{
      		label:'苹果',
      		value:0
      	},
      	{
      		label:'香蕉',
      		value:1
      	},
      	{
      		label:'西瓜',
      		value:2
      	},
      	]
      }
	},
	methods:{

	},
	mounted(){

	}
}

</script>

<style>
.indexPage	{
	height: 460px;
}


</style>