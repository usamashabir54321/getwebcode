<template>
	<header class="navbar navbar-sticky navbar-expand-lg navbar-dark">
		<div class="container position-relative">
			<nuxt-link class="navbar-brand" to="/template/app-land-1/index-2">
				<img class="navbar-brand-regular" src="/preview/app_land_1/assets/img/logo/logo-white.png" alt="brand-logo">
				<img class="navbar-brand-sticky" src="/preview/app_land_1/assets/img/logo/logo.png" alt="sticky brand-logo">
			</nuxt-link>
			<button class="navbar-toggler d-lg-none" type="button" data-toggle="navbarToggler" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
			</button>

			<div class="navbar-inner">
				<!--  Mobile Menu Toggler -->
				<button class="navbar-toggler d-lg-none" type="button" data-toggle="navbarToggler" aria-label="Toggle navigation">
					<span class="navbar-toggler-icon"></span>
				</button>
				<nav>
					<ul class="navbar-nav" id="navbar-nav">
						<li class="nav-item dropdown">
							<a class="nav-link dropdown-toggle" href="javascript:;" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Home </a>
							<ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
								<li>
									<nuxt-link class="dropdown-item" to="/template/app-land-1/">Homepage-1</nuxt-link>
								</li>
								<li>
									<nuxt-link class="dropdown-item" to="/template/app-land-1/index-2">Homepage-2</nuxt-link>
								</li>
								<li>
									<nuxt-link class="dropdown-item" to="/template/app-land-1/index-3">Homepage-3</nuxt-link>
								</li>
								<li>
									<nuxt-link class="dropdown-item" to="/template/app-land-1/index-4">Homepage-4</nuxt-link>
								</li>
								<li>
									<nuxt-link class="dropdown-item" to="/template/app-land-1/index-5">Homepage-5</nuxt-link>
								</li>
								<li>
									<nuxt-link class="dropdown-item" to="/template/app-land-1/index-6">Homepage-6</nuxt-link>
								</li>
							</ul>
						</li>
						<li class="nav-item dropdown">
							<a class="nav-link dropdown-toggle" href="javascript:;" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Pages </a>
							<ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
								<li class="dropdown-submenu"><a class="dropdown-item dropdown-toggle" href="javascript:;">Inner Pages<span class="badge badge-pill badge-warning ml-2">New</span></a>
									<ul class="dropdown-menu">
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/pricing">Pricing</nuxt-link>
										</li>
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/download">Download</nuxt-link>
										</li>
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/newsletter">Newsletter</nuxt-link>
										</li>
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/thank-you">Thank you</nuxt-link>
										</li>
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/coming-soon">Coming Soon</nuxt-link>
										</li>
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/404">404</nuxt-link>
										</li>
									</ul>
								</li>
								<li class="dropdown-submenu"><a class="dropdown-item dropdown-toggle" href="javascript:;">Blog Pages</a>
									<ul class="dropdown-menu">
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/blog-two-column">Blog- 2 Column</nuxt-link>
										</li>
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/blog-three-column">Blog- 3 Column</nuxt-link>
										</li>
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/blog-left-sidebar">Blog- Left Sidebar</nuxt-link>
										</li>
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/blog-right-sidebar">Blog- Right Sidebar</nuxt-link>
										</li>
									</ul>
								</li>
								<li class="dropdown-submenu"><a class="dropdown-item dropdown-toggle" href="javascript:;">Blog Details</a>
									<ul class="dropdown-menu">
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/blog-details-left-sidebar">Blog Details- Left Sidebar</nuxt-link>
										</li>
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/blog-details-right-sidebar">Blog Details- Right Sidebar</nuxt-link>
										</li>
									</ul>
								</li>
								<li class="dropdown-submenu"><a class="dropdown-item dropdown-toggle" href="javascript:;">Accounts<span class="badge badge-pill badge-warning ml-2">New</span></a>
									<ul class="dropdown-menu">
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/login">Login</nuxt-link>
										</li>
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/signup">Signup</nuxt-link>
										</li>
										<li>
											<nuxt-link class="dropdown-item" to="/template/app-land-1/forgot">Reset Password</nuxt-link>
										</li>
									</ul>
								</li>
							</ul>
						</li>
					</ul>
				</nav>
			</div>
		</div>
	</header>
</template>