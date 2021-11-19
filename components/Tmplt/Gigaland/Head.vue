<template>
	<header :class="tmplt == 'retro' ? 'header-light scroll-light' : ''" class="transparent">
		<div class="container">
			<div class="row">
				<div class="col-md-12">
					<div class="de-flex sm-pt10">
						<div class="de-flex-col">
							<div class="de-flex-col">
								<!-- logo begin -->
								<div id="logo">
									<nuxt-link :to="`/template/gigaland/${tmplt}`">
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
									<a>Home<span></span></a>
									<ul>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}`">Homepage 1</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/index-2`">Homepage 2</nuxt-link></li>
										<li v-if="tmplt != 'retro'"><nuxt-link :to="`/template/gigaland/${tmplt}/index-3`">Homepage 3</nuxt-link></li>
										<li v-if="tmplt != 'retro'"><nuxt-link :to="`/template/gigaland/${tmplt}/index-4`">Homepage 4</nuxt-link></li>
										<li v-if="tmplt == 'light'"><nuxt-link :to="`/template/gigaland/${tmplt}/index-5`">Homepage 5</nuxt-link></li>
										<li v-if="tmplt == 'light'"><nuxt-link :to="`/template/gigaland/${tmplt}/index-6`">Homepage 6</nuxt-link></li>
									</ul>
								</li>
								<li>
									<a>Explore<span></span></a>
									<ul>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/explore`">Explore</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/explore-2`">Explore 2</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/collection`">Collections</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/live-auction`">Live Auction</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/item-details`">Item Details</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/help-center`">Help Center</nuxt-link></li>
									</ul>
								</li>
								<li v-if="tmplt == 'dark' || tmplt == 'light'" class="menu-item-has-children has-child">
									<a href="#">Pages<span></span></a><span></span>
									<ul>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/author`">Author</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/profile`">Profile</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/wallet`">Wallet</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/create-options`">Create</nuxt-link></li>
										<li v-if="tmplt == 'light'"><nuxt-link :to="`/template/gigaland/${tmplt}/news`">News</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/gallery`">Gallery</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/login`">Login</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/login-2`">Login 2</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/register`">Register</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/contact`">Contact Us</nuxt-link></li>
									</ul>
								</li>
								<li v-if="tmplt == 'dark' || tmplt == 'light'" class="menu-item-has-children has-child">
									<a href="#">Elements<span></span></a><span></span>
									<ul>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/icons-elegant`">Elegant Icons</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/icons-etline`">Etline Icons</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/icons-font-awesome`">Font Awesome Icons</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/accordion`">Accordion</nuxt-link></li> 
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/alerts`">Alerts</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/counters`">Counters</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/modal`">Modal</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/popover`">Popover</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/pricing-table`">Pricing Table</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/progress-bar`">Progress Bar</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/tabs`">Tabs</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/tooltips`">Tooltips</nuxt-link></li>
									</ul>
								</li>
								<li v-if="tmplt == 'grey' || tmplt == 'retro'">
									<a>Author<span></span></a>
									<ul>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/author`">Author</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/profile`">Profile</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/wallet`">Wallet</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/create-options`">Create</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/login`">Login</nuxt-link></li>
									</ul>
								</li>
								<li>
									<a>Stats<span></span></a>
									<ul>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/activity`">Activity</nuxt-link></li>
										<li><nuxt-link :to="`/template/gigaland/${tmplt}/rankings`">Rankings</nuxt-link></li>
									</ul>
								</li>
							</ul>
							<!-- mainmenu close -->
							<div class="menu_side_area">
								<nuxt-link :to="`/template/gigaland/${tmplt}/wallet`" class="btn-main btn-wallet"><i class="icon_wallet_alt"></i><span>Connect Wallet</span></nuxt-link>
								<span id="menu-btn"></span>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</header>
</template>

<script>
	export default {
		props: ['tmplt'],
	}
</script>