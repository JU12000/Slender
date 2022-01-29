<script lang="ts">
	import { Hero } from '$lib';
</script>

<Hero>
	<div class="hero--slot">
		<h1>Hero Text</h1>
	</div>
</Hero>

<style lang="scss">
	.hero--slot {
		align-items: center;
		background-color: black;
		color: white;
		display: flex;
		height: 100%;
		justify-content: center;
	}
</style>
