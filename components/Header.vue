<template>
	<div class="header">
		<div class="wrapper">
			<img src="~/assets/logo.svg">
		</div>
	</div>
</template>

<style scoped>
.header {
	padding-top: 20px;
	padding-bottom: 8px;
	padding-left: 40px;
	padding-right: 40px;
	position: relative;
	z-index: 100;
	background-color: #3f51b5;
}

.header img {
	height: 60px;
}

@media screen and (max-width: 1240px) {
	.header {
		padding-left: 20px;
	}
}
</style>