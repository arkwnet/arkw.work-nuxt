<template>
	<div class="main">
		<Navi />
		<div class="wrapper">
			<div class="wrapper-left">
				<h1>製品情報</h1>
				<p></p>
				<br>
				<h1>コンテンツ</h1>
				<p></p>
				<br>
				<h1>リンク集</h1>
				<p></p><br>
			</div>
			<div class="wrapper-right">
				<h1>トピックス</h1>
				<p></p>
				<br>
				<h1>更新情報</h1>
				<p></p>
				<br>
				<h1>プロフィール</h1>
				<p></p>
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