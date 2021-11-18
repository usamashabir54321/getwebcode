<template>
	<div id="gigaland_templt">
		<Nuxt keep-alive/>
	</div>
</template>

<script>
	export default {
		head: {
            title: 'GIGALAND',
            link:[
                { rel:'stylesheet' , type:'text/css' , href:'/preview/gigaland/assets/css/bootstrap.min.css' , id:'bootstrap' },
                { rel:'stylesheet' , type:'text/css' , href:'/preview/gigaland/assets/css/bootstrap-grid.min.css' , id:'bootstrap-grid' },
                { rel:'stylesheet' , type:'text/css' , href:'/preview/gigaland/assets/css/bootstrap-reboot.min.css' , id:'bootstrap-reboot' },
                { rel:'stylesheet' , type:'text/css' , href:'/preview/gigaland/assets/css/animate.css' },
                { rel:'stylesheet' , type:'text/css' , href:'/preview/gigaland/assets/css/owl.carousel.css' },
                { rel:'stylesheet' , type:'text/css' , href:'/preview/gigaland/assets/css/owl.theme.css' },
                { rel:'stylesheet' , type:'text/css' , href:'/preview/gigaland/assets/css/owl.transitions.css' },
                { rel:'stylesheet' , type:'text/css' , href:'/preview/gigaland/assets/css/magnific-popup.css' },
                { rel:'stylesheet' , type:'text/css' , href:'/preview/gigaland/assets/css/style.css' },
                { rel:'stylesheet' , type:'text/css' , href:'/preview/gigaland/assets/css/de-grey.css' },
                { rel:'stylesheet' , type:'text/css' , href:'/preview/gigaland/assets/css/colors/scheme-04.css' },
                { rel:'stylesheet' , type:'text/css' , href:'/preview/gigaland/assets/css/coloring.css' },
            ],
            script:[
                { src:'/preview/gigaland/assets/js/jquery.min.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/bootstrap.min.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/bootstrap.bundle.min.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/wow.min.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/jquery.isotope.min.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/easing.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/owl.carousel.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/validation.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/jquery.magnific-popup.min.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/enquire.min.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/jquery.plugin.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/jquery.countTo.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/jquery.countdown.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/jquery.lazy.min.js' , defer:'defer' },
                { src:'/preview/gigaland/assets/js/jquery.lazy.plugins.min.js' , defer:'defer' },
            ],
        },
	}
</script>