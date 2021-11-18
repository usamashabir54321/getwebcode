<template>
	<div id="web_home_id">
		<WebHeader />
		<Nuxt keep-alive />
	</div>
</template>

<script>
	export default {
		head: {
			title: 'GET WEB CODE',
			link:[
				{ rel:'stylesheet' , type:'text/css' , href:'/web/assets/css/bootstrap.min.css' },
			],
		},
	}
</script>