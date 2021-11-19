<template>
	<div id="templt_id" :class="$nuxt.$route.name == 'template-app-land-1-login' ? 'homepage-5' : ''" class="inner accounts">
		<div id="scrollUp" title="Scroll To Top"><i class="fas fa-arrow-up"></i></div>
		<div class="main">
			<TmpltAppLand1Head />
			<Nuxt keep-alive/>
		</div>
	</div>
</template>

<script>
	export default {
		head: {
			title: 'MY APP LAND',
			link: [
				{ rel: "stylesheet" , type: "text/css" , href:'/preview/app_land_1/assets/css/style.css' },
			],
			script: [
				{ src:'/preview/app_land_1/assets/js/jquery/jquery.min.js' },
				{ src:'/preview/app_land_1/assets/js/bootstrap/popper.min.js' },
				{ src:'/preview/app_land_1/assets/js/bootstrap/bootstrap.min.js' },
			],
		},
	}
</script>