<template>
	Lorem ipsum dolor sit amet, consectetur adipisicing elit.
	Architecto fuga sunt tempora veniam voluptatem. Ab, alias aliquam
	aliquid dolorem doloribus dolorum, inventore minus necessitatibus nesciunt
	reiciendis sed ullam voluptatem voluptatum!
	
	{{ timer }}
	
</template>

<script>
export default {
	name: 'Timer',
	data() {
		return {
			timer: 0
		}
	},
	mounted() {
		setInterval(() => {
			this.timer++
		}, 1000)
	}
}
</script>

<style scoped>

</style>
