<template>
	<section id="home" class="section welcome-area inner-area coming-soon bg-overlay h-100vh overflow-hidden">
		<div class="container h-100">
			<div class="row align-items-center justify-content-center h-100">
				<div class="col-12 col-md-8">
					<div class="welcome-intro text-center">
						<h1 class="text-white">We are coming soon!</h1>
						<p class="text-white my-4">Our website is under construction. We'll be here soon with our new awesome site, subscribe to be notified.</p>
						<div class="countdown-times mb-4">
							<div class='countdown d-flex justify-content-center' data-date="2022-12-09"></div>
						</div>
						<!-- Subscribe Form -->
						<div class="subscribe-form d-flex align-items-center mx-auto">
							<input type="email" class="form-control" placeholder="info@yourmail.com">
							<button type="submit" class="btn btn-bordered">Notify</button>
						</div>
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
            title: 'LANDING 1 COMING SOON',
            script: [
				{ src:'/preview/app_land_1/assets/js/plugins/plugins.min.js' , defer: 'defer' },
			],
        },
	}
</script>