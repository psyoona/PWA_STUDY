<template>
	<div id="app">
		<h1>안녕하세요~!</h1>
		<router-view></router-view>
		<hr>
		<p>라우터 링크 사용:
			<router-link to="/main">메인 페이지</router-link>
			<router-link to="/sub">서브 페이지</router-link>
		</p>
	</div>
</template>