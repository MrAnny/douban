<template>
	<div>
		<Myheader txt='书影音'>
			<img src='../../assets/images/ic_actionbar_search_icon.png' class='leftImg' slot='left'/>
			<img src='../../assets/images/ic_chat_green.png' class='rightImg' slot='right'/>

		</Myheader>
	</div>
</template>

<script>
	import Myheader from '../../components/header'

	export default {
		components: {
			Myheader
		}
	}

</script>