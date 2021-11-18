<template>
	<header class="py-3 border-bottom">
		<div class="container d-flex flex-wrap justify-content-center">
			<nuxt-link to="/" id="logo_sec" class="d-flex align-items-center mb-3 mb-lg-0 me-lg-auto text-dark text-decoration-none">
				<span class="fs-4">C <img id="logo_img" src="/world1.png"> D E</span>
			</nuxt-link>
			<ul class="nav me-auto">
				<li class="nav-item"><a href="#" class="nav-link link-dark px-2 active" aria-current="page">Home</a></li>
				<li class="nav-item"><a href="#" class="nav-link link-dark px-2">Features</a></li>
				<li class="nav-item"><a href="#" class="nav-link link-dark px-2">Pricing</a></li>
				<li class="nav-item"><a href="#" class="nav-link link-dark px-2">FAQs</a></li>
				<li class="nav-item"><a href="#" class="nav-link link-dark px-2">About</a></li>
			</ul>
			<form class="col-12 col-lg-auto mb-3 mb-lg-0">
				<input type="search" class="form-control" placeholder="Search..." aria-label="Search">
			</form>
		</div>
	</header>
</template>