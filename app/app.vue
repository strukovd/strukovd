<template>
	<section id="app">
		<h1 class="animated-text points-background">
			<div>Струков Дмитрий</div>
			<span class="major gradient-text">Fullstack-developer</span>
		</h1>
	</section>
</template>

<script lang="ts" setup>

</script>

<style lang="scss">
#app {
	h1 {
		.major {
			font-size: 1.4em;
		}
	}
}

@keyframes zoomIn {
  from {
    opacity: 0;
    transform: scale(0.5);
  }
  to {
    opacity: 1;
    transform: scale(1);
  }
}

.animated-text {
  animation: zoomIn 0.5s ease-out forwards;
}
</style>