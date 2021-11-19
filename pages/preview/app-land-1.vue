<template>
	<div id="prevw_pg" class="container-fluid p-5">

		<div class="sec_title"><h2>Select Preview In Nuxt Js</h2></div>

		<div v-for="(obj1,index) in items" :key="index">
			<div class="row_title mt-3 mb-3"><h3>{{ obj1.item_title }} <a :href="obj1.link" target="_blank" class="btn btn-success float-end">Template Preview</a></h3></div>
			<div class="row">
				<div v-for="(obj2,index) in obj1.pages" :key="index" class="col-md-2 col-sm-6 col-xs-12 item p-3">
					<div class="img_sec"><a :href="obj2.link" target="_blank"><img :src="`/preview/app_land_1/${obj2.src}`"></a></div>
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
			title: 'LANDING PAGES FIRST APP',
		},
		data () {
			return {
				items: [
					{
						item_title: 'LANDING PAGES FIRST APP',
						link: '/template/app-land-1/',
						pages: [
							{title:'DEMO 1',src:'01.png' , link: '/template/app-land-1/'},
							{title:'DEMO 2',src:'02.png' , link: '/template/app-land-1/index-2'},
							{title:'DEMO 3',src:'03.png' , link: '/template/app-land-1/index-3'},
							{title:'DEMO 4',src:'04.png' , link: '/template/app-land-1/index-4'},
							{title:'DEMO 5',src:'05.png' , link: '/template/app-land-1/index-5'},
							{title:'DEMO 6',src:'06.png' , link: '/template/app-land-1/index-6'},
							{title:'REVIEWS',src:'reviews.png' , link: '/template/app-land-1/reviews'},
							{title:'PRICING',src:'pricing.png' , link: '/template/app-land-1/pricing'},
							{title:'FAQ',src:'faq.png' , link: '/template/app-land-1/faq'},
							{title:'CONTACT',src:'contact.png' , link: '/template/app-land-1/contact'},
							{title:'BLOG - 2 COLUMN',src:'blog-01.png' , link: '/template/app-land-1/blog-two-column'},
							{title:'BLOG - 3 COLUMN',src:'blog-02.png' , link: '/template/app-land-1/blog-three-column'},
							{title:'BLOG - LEFT SIDEBAR',src:'blog-03.png' , link: '/template/app-land-1/blog-left-sidebar'},
							{title:'BLOG - RIGHT SIDEBAR',src:'blog-04.png' , link: '/template/app-land-1/blog-right-sidebar'},
							{title:'BLOG DETAILS - LEFT SIDEBAR',src:'blog-05.png' , link: '/template/app-land-1/blog-details-left-sidebar'},
							{title:'BLOG DETAILS - RIGHT SIDEBAR',src:'blog-06.png' , link: '/template/app-land-1/blog-details-right-sidebar'},
							{title:'DOWNLOAD',src:'download.png' , link: '/template/app-land-1/download'},
							{title:'LOGIN',src:'login.png' , link: '/template/app-land-1/login'},
							{title:'404',src:'404.png' , link: '/template/app-land-1/404'},
							{title:'RESET PASSWORD',src:'forgot.png' , link: '/template/app-land-1/forgot'},
							{title:'COMING SOON',src:'coming-soon.png' , link: '/template/app-land-1/coming-soon'},
							{title:'SIGN UP',src:'signup.png' , link: '/template/app-land-1/signup'},
							{title:'THANK YOU',src:'thank-you.png' , link: '/template/app-land-1/thank-you'},
							{title:'NEWSLETTER',src:'newsletter.png' , link: '/template/app-land-1/newsletter'},
						],
					},
				],
			}
		},
	}
</script>