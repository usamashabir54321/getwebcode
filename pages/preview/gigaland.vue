<template>
	<div id="prevw_pg" class="container-fluid p-5">

		<div class="sec_title"><h2>Select Preview In Nuxt Js</h2></div>

		<div v-for="(obj1,index) in items" :key="index">
			<div class="row_title mt-3 mb-3"><h3>{{ obj1.item_title }} <a :href="obj1.link" target="_blank" class="btn btn-success float-end">Template Preview</a></h3></div>
			<div class="row">
				<div v-for="(obj2,index) in obj1.pages" :key="index" class="col-md-2 col-sm-6 col-xs-12 item p-3">
					<div class="img_sec"><a :href="obj2.link" target="_blank"><img :src="`/preview/gigaland/${obj2.src}`"></a></div>
					<h4>{{ obj2.title }}</h4>
				</div>
			</div>
		</div>

	</div>
</template>

<script>
	export default {
		layout: 'web',
		head: {
			title: 'GIGALAND WEB TEMPLATE PREVIEW',
		},
		data () {
			return {
				items: [
					{
						item_title: 'Dark Color Scheme',
						link: '/template/gigaland/dark',
						pages: [
							{title:'Homepage 1 Dark',src:'preview%20(2).jpg' , link: '/template/gigaland/dark/'},
							{title:'Homepage 2 Dark',src:'preview%20(4).jpg' , link: '/template/gigaland/dark/index-2'},
							{title:'Homepage 3 Dark',src:'preview%20(6).jpg' , link: '/template/gigaland/dark/index-3'},
							{title:'Homepage 4 Dark',src:'preview%20(8).jpg' , link: '/template/gigaland/dark/index-4'},
							{title:'Profile Dark',src:'dark-profile.jpg' , link: '/template/gigaland/dark/profile'},
							{title:'Create Dark',src:'dark-create.jpg' , link: '/template/gigaland/dark/create-options'},
							{title:'Explore Dark',src:'dark-explore.jpg' , link: '/template/gigaland/dark/explore'},
							{title:'Wallet Dark',src:'dark-wallet.jpg' , link: '/template/gigaland/dark/wallet'},
							{title:'Help Center Dark',src:'help-center-dark.jpg' , link: '/template/gigaland/dark/help-center'},
							{title:'Rankings Dark',src:'dark-rankings.jpg' , link: '/template/gigaland/dark/rankings'},
							{title:'Author Dark',src:'dark-author.jpg' , link: '/template/gigaland/dark/author'},
							{title:'Collection Dark',src:'dark-collection.jpg' , link: '/template/gigaland/dark/collection'},
							{title:'Item Details Dark',src:'dark-item-details.jpg' , link: '/template/gigaland/dark/item-details'},
							{title:'Activity Dark',src:'dark-activity.jpg' , link: '/template/gigaland/dark/activity'},
							{title:'Login Dark',src:'dark-login.jpg' , link: '/template/gigaland/dark/login'},
							{title:'News Dark',src:'dark-news.jpg' , link: '/template/gigaland/dark/gallery'},
						],
					},
					{
						item_title: 'Light Color Scheme',
						link: '/template/gigaland/light',
						pages: [
							{title:'Homepage 1 Light',src:'preview%20(1).jpg' , link: '/template/gigaland/light/'},
							{title:'Homepage 2 Light',src:'preview%20(3).jpg' , link: '/template/gigaland/light/index-2'},
							{title:'Homepage 3 Light',src:'preview%20(5).jpg' , link: '/template/gigaland/light/index-3'},
							{title:'Homepage 4 Light',src:'preview%20(7).jpg' , link: '/template/gigaland/light/index-4'},
							{title:'Homepage 5 Light',src:'light-homepage-5.jpg' , link: '/template/gigaland/light/index-5'},
							{title:'Homepage 6 Light',src:'light-homepage-6.jpg' , link: '/template/gigaland/light/index-6'},
							{title:'Profile Light',src:'light-profile.jpg' , link: '/template/gigaland/light/profile'},
							{title:'Create Light',src:'light-create.jpg' , link: '/template/gigaland/light/create-options'},
							{title:'Explore Light',src:'light-explore.jpg' , link: '/template/gigaland/light/explore'},
							{title:'Wallet Light',src:'light-wallet.jpg' , link: '/template/gigaland/light/wallet'},
							{title:'Help Center Light',src:'help-center-light.jpg' , link: '/template/gigaland/light/help-center'},
							{title:'Rankings Light',src:'light-rankings.jpg' , link: '/template/gigaland/light/rankings'},
							{title:'Author Light',src:'light-author.jpg' , link: '/template/gigaland/light/author'},
							{title:'Collection Light',src:'light-collection.jpg' , link: '/template/gigaland/light/collection'},
							{title:'Item Details Light',src:'light-item-details.jpg' , link: '/template/gigaland/light/item-details'},
							{title:'Activity Light',src:'light-activity.jpg' , link: '/template/gigaland/light/activity'},
							{title:'Login Light',src:'light-login.jpg' , link: '/template/gigaland/light/login'},
							{title:'News Light',src:'light-news.jpg' , link: '/template/gigaland/light/news'},
						],
					},
					{
						item_title: 'Grey Color Scheme',
						link: '/template/gigaland/grey',
						pages: [
							{title:'Homepage 1 Grey',src:'grey-homepage-1.jpg' , link: '/template/gigaland/grey/'},
							{title:'Homepage 2 Grey',src:'grey-homepage-2.jpg' , link: '/template/gigaland/grey/index-2'},
							{title:'Homepage 3 Grey',src:'grey-homepage-3.jpg' , link: '/template/gigaland/grey/index-3'},
							{title:'Homepage 4 Grey',src:'grey-homepage-4.jpg' , link: '/template/gigaland/grey/index-4'},
							{title:'Profile Grey',src:'grey-profile.jpg' , link: '/template/gigaland/grey/profile'},
							{title:'Create Grey',src:'grey-create.jpg' , link: '/template/gigaland/grey/create-options'},
							{title:'Explore Grey',src:'grey-explore.jpg' , link: '/template/gigaland/grey/explore'},
							{title:'Wallet Grey',src:'grey-wallet.jpg' , link: '/template/gigaland/grey/wallet'},
							{title:'Help Center Grey',src:'help-center-grey.jpg' , link: '/template/gigaland/grey/help-center'},
							{title:'Rankings Grey',src:'grey-rankings.jpg' , link: '/template/gigaland/grey/rankings'},
							{title:'Author Grey',src:'grey-author.jpg' , link: '/template/gigaland/grey/author'},
							{title:'Collection Grey',src:'grey-collection.jpg' , link: '/template/gigaland/grey/collection'},
							{title:'Item Details Grey',src:'grey-item-details.jpg' , link: '/template/gigaland/grey/item-details'},
							{title:'Activity Grey',src:'grey-activity.jpg' , link: '/template/gigaland/grey/activity'},
							{title:'Login Grey',src:'grey-login.jpg' , link: '/template/gigaland/grey/login'},
						],
					},
					{
						item_title: 'Retro Color Scheme',
						link: '/template/gigaland/retro',
						pages: [
							{title:'Homepage Retro',src:'retro-homepage-1.jpg' , link: '/template/gigaland/retro/'},
							{title:'Profile Retro',src:'retro-profile.jpg' , link: '/template/gigaland/retro/profile'},
							{title:'Create Retro',src:'retro-create.jpg' , link: '/template/gigaland/retro/create-options'},
							{title:'Explore Retro',src:'retro-explore.jpg' , link: '/template/gigaland/retro/explore'},
							{title:'Wallet Retro',src:'retro-wallet.jpg' , link: '/template/gigaland/retro/wallet'},
							{title:'Help Center Retro',src:'retro-help-center.jpg' , link: '/template/gigaland/retro/help-center'},
							{title:'Rankings Retro',src:'retro-rankings.jpg' , link: '/template/gigaland/retro/rankings'},
							{title:'Author Retro',src:'retro-author.jpg' , link: '/template/gigaland/retro/author'},
							{title:'Collection Retro',src:'retro-collection.jpg' , link: '/template/gigaland/retro/collection'},
							{title:'Item Details Retro',src:'retro-item-details.jpg' , link: '/template/gigaland/retro/item-details'},
							{title:'Activity Retro',src:'retro-activity.jpg' , link: '/template/gigaland/retro/activity'},
							{title:'Login Retro',src:'retro-login.jpg' , link: '/template/gigaland/retro/login'},
						],
					},
				],
			}
		},
	}
</script>