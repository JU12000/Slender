<script lang="ts">
	export let imageAlt: string = 'No Image';
	export let imageSource: string = 'https://via.placeholder.com/1080';
	export let size: size = 'md';
</script>

<div class="hero {size}">
	<div class="hero--text-container">
		<slot />
	</div>
	<div class="hero--image-container">
		<img src={imageSource} alt={imageAlt} />
	</div>
</div>

<style lang="scss">
	.hero {
		display: flex;

		.hero-- {
			&text-container {
				min-width: 50%;
			}

			&image-container {
				min-width: 50%;
				overflow: hidden;
			}
		}
	}

	.lg {
		max-height: 40vh;
	}

	.md {
		max-height: 30vh;
	}

	.sm {
		height: 20vh;
	}
</style>
