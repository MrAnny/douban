<template>
	<div>
		<Myheader txt='我的'>
			<img src='../../assets/images/ic_settings.png' class='rightImg' slot='right'/>
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