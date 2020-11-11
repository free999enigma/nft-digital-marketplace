<template>
	<section class="flex home-container">
		<h1 class="title">Buy Digital Art</h1>
	</section>
</template>

<script>
import Components from "@/components/index";

export default {
	components: {
		...Components
	}
};
</script>

<style scoped>
.home-container {
	flex-direction: column;
	align-items: center;
}

.title {
	font-size: 5em;
	margin: 0;
	padding: 50px 0 20px 0;
	font-family: "Fredoka One", sans-serif;
}

.connect-btn {
	margin: 30px 0;
}

.withdraw-btn {
	background-color: rgb(22, 128, 57);
}
</style>
