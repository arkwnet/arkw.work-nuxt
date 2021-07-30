<template>
	<div class="main">
		<Navi />
		<div class="wrapper">
			<div class="wrapper-left">
				<h1>製品情報</h1>
				<p>準備中</p>
			</div>
			<div class="wrapper_right">
				<h1>トピックス</h1>
				<p>準備中</p>
			</div>
		</div>
	</div>
</template>

<style scoped>
.main {
	padding-bottom: 20px;
	background-color: #fff;
}

.wrapper {
	width: 1200px;
	margin: auto;
	padding: 20px 5px;
	overflow: hidden;
	box-sizing: border-box;
}

.wrapper h1 {
	padding-top: 20px;
	padding-bottom: 5px;
	font-size: 26px;
	font-weight: normal;
	padding-top: 20px;
	color: #3f51b5;
	overflow: hidden;
}

.wrapper p {
	padding: 5px 0;
}

.wrapper-left {
	width: 440px;
	float: left;
}

.wrapper-right {
	width: 700px;
	float: right;
}
</style>

<script>
import Navi from "~/components/Navi.vue"
export default {
	components: {
		Navi
	},
}
</script>