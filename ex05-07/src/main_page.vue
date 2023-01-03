<template lang="html">
	<div>
		<h2>메인 페이지입니다.</h2>
		<button @click="moveToSubPage">서브 페이지로 이동(라우터 함수 이용)</button>
	</div>
</template>

<script>
	export default {
		methods: {
			moveToSubPage(){
				this.$router.push('/sub');
			}
		}
	}
</script>