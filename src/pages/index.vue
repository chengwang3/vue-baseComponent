<template>
	<div class="indexPage">
		<v-pagenation :total="10" :pageSize="3"></v-pagenation>
	</div>

</template>

<script>
import VPagenation from '../components/base/pagenation'	
export default {
	components:{
		VPagenation
	},
	data(){
      return {
        
	}
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