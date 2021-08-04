<template>
	<div class="logo">
		<splitter></splitter>
	</div>
</template>

<script>
import Splitter from "../components/Splitter.vue";
export default {
	name: "Home",
	components: {
		Splitter,
	},
};
</script>
<style lang="scss" scoped>
.logo {
	display: flex;
	justify-content: center;
	align-items: center;
}
</style>
