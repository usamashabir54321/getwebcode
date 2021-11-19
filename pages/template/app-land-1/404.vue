<template>
	<section id="home" class="section welcome-area inner-area bg-overlay h-100vh overflow-hidden">
		<div class="container h-100">
			<div class="row align-items-center justify-content-center h-100">
				<div class="col-12 col-md-7">
					<div class="welcome-intro error-area text-center">
						<h1 class="text-white">404</h1>
						<p class="text-white my-4">The page you are looking for might have been removed had its name changed or is temporarily unavailable.</p>
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
            title: 'LANDING 1 404 ERROR PAGE',
        },
	}
</script>