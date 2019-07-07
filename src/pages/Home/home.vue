<template>
	<div>
		<Myheader bol='true'>
			
			<img src='../../assets/images/ic_chat_white.png' class='rightImg' slot='right'/>
			<div slot='search' class='search'>
				<input type='text' placeholder='影视 图书 唱片 小组等'/>
				<img src='../../assets/images/ic_group_search_small.png' class='searchImg'/>
				<img src='../../assets/images/ic_scan_gray.png' class='scanImg'/>
			</div>
		</Myheader>
		<Banner swiperid='go'>
			<div slot='swiper-con' class='swiper-slide'>
				<img src='../../assets/images/banner/01.jpg'/>
			</div>
			<div slot='swiper-con' class='swiper-slide'>
				<img src='../../assets/images/banner/02.jpg'/>
			</div>
			<div slot='swiper-con' class='swiper-slide'>
				<img src='../../assets/images/banner/03.jpg'/>
			</div>
		</Banner>
	</div>
</template>

<script>
import Myheader from '../../components/header'
import Banner from '../../components/banner'

export default {
	components: {
		Myheader,
		Banner
	}
}
</script>