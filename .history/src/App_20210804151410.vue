<template>
	<router-view />
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&display=swap");

* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	font-family: "Space Mono", monospace;
	font-size: 2.4rem;
}
body {
	background-color: hsl(185, 41%, 84%);
}
html {
	font-size: 62.5%;
	@media only screen and (min-width: 1800px) {
		font-size: 82.5%;
	}
	@media only screen and (max-width: 1000px) {
		font-size: 52.5%;
	}
	@media only screen and (max-width: 350px) {
		font-size: 32.5%;
	}
}
</style>
