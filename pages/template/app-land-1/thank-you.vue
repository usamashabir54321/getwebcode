<template>
	<section id="home" class="section welcome-area inner-area bg-overlay h-100vh overflow-hidden">
		<div class="container h-100">
			<div class="row align-items-center h-100">
				<div class="col-12 col-md-8">
					<div class="welcome-intro">
						<h1 class="text-white">Thank you for downloading sApp</h1>
						<p class="text-white my-4">We are continuously creating new stuff for sApp and trying to keep it up to date with the new technologies that might appear along the development process. We appreciate each of you who downloaded or purchased our theme and we take your suggestions into consideration every time.</p>
						<nuxt-link to="/template/app-land-1/index-2" class="btn sApp-btn text-uppercase">Go to Homepage</nuxt-link>
					</div>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
	export default {
		layout: 'landing_pgs/app_land_1/2_lty',
		head: {
            title: 'LANDING 1 THANKS YOU PAGE',
        },
	}
</script>