<template>
	<header class="transparent scroll-dark">
		<div class="container">
			<div class="row">
				<div class="col-md-12">
					<div class="de-flex sm-pt10">
						<div class="de-flex-col">
							<div class="de-flex-col">
								<!-- logo begin -->
								<div id="logo">
									<nuxt-link to="/template/gigaland/grey">
										<img alt="" src="/preview/gigaland/assets/images/logo-3.png" />
									</nuxt-link>
								</div>
								<!-- logo close -->
							</div>
							<div class="de-flex-col">
								<input id="quick_search" class="xs-hide style-2" name="quick_search" placeholder="search item here..." type="text" />
							</div>
						</div>
						<div class="de-flex-col header-col-mid">
							<!-- mainmenu begin -->
							<ul id="mainmenu">
								<li>
									<nuxt-link to="/template/gigaland/grey">Home<span></span></nuxt-link>
									<ul>
										<li><nuxt-link to="/template/gigaland/grey">Homepage 1</nuxt-link></li>
										<li><nuxt-link to="/template/gigaland/grey/index-2">Homepage 2</nuxt-link></li>
										<li><nuxt-link to="/template/gigaland/grey/index-3">Homepage 3</nuxt-link></li>
										<li><nuxt-link to="/template/gigaland/grey/index-4">Homepage 4</nuxt-link></li>
									</ul>
								</li>
								<li>
									<nuxt-link to="/template/gigaland/grey/explore">Explore<span></span></nuxt-link>
									<ul>
										<li><nuxt-link to="/template/gigaland/grey/explore">Explore</nuxt-link></li>
										<li><nuxt-link to="/template/gigaland/grey/explore-2">Explore 2</nuxt-link></li>
										<li><nuxt-link to="/template/gigaland/grey/collection">Collections</nuxt-link></li>
										<li><nuxt-link to="/template/gigaland/grey/live-auction">Live Auction</nuxt-link></li>
										<li><nuxt-link to="/template/gigaland/grey/item-details">Item Details</nuxt-link></li>
										<li><nuxt-link to="/template/gigaland/grey/help-center">Help Center</nuxt-link></li>
									</ul>
								</li>
								<li>
									<nuxt-link to="/template/gigaland/grey/author">Author<span></span></nuxt-link>
									<ul>
										<li><nuxt-link to="/template/gigaland/grey/author">Author</nuxt-link></li>
										<li><nuxt-link to="/template/gigaland/grey/profile">Profile</nuxt-link></li>
										<li><nuxt-link to="/template/gigaland/grey/wallet">Wallet</nuxt-link></li>
										<li><nuxt-link to="/template/gigaland/grey/create-options">Create</nuxt-link></li>
										<li><nuxt-link to="/template/gigaland/grey/login">Login</nuxt-link></li>
									</ul>
								</li>                                    
								<li>
									<nuxt-link to="#">Stats<span></span></nuxt-link>
									<ul>
										<li><nuxt-link to="/template/gigaland/grey/activity">Activity</nuxt-link></li>
										<li><nuxt-link to="/template/gigaland/grey/rankings">Rankings</nuxt-link></li>
									</ul>
								</li>
							</ul>
							<!-- mainmenu close -->
							<div class="menu_side_area">
								<nuxt-link to="/template/gigaland/grey/wallet" class="btn-main btn-wallet"><i class="icon_wallet_alt"></i><span>Connect Wallet</span></nuxt-link>
								<span id="menu-btn"></span>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</header>
</template>