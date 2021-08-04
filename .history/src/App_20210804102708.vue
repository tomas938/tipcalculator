<template>
	<router-view />
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&display=swap");
$strong-cyan: hsl(172, 67%, 45%);
$dark-cyan: hsl(186, 14%, 43%);
$grayish-cyan: hsl(184, 14%, 43%);
$lower-grayish-cyan: hsl(184, 14%, 56%);
$light-grayish-cyan: hsl(185, 41%, 84%);
$lighter-grayish-cyan: hsl(189, 41%, 97%);
$white: hsl(0, 0%, 100%);
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
	@media only screen and (max-width: 760px) {
		font-size: 62.5%;
	}
}
</style>
