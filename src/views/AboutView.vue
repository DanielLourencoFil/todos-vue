<template>
	<div class="about">
		<h1>This is an about page</h1>
		<p>
			Vue Todos is a CRUD Todo tracking application created for a Vue 3 Crash
			Course by John Komarnicki. <br />Track your daily task's using this todo
			tracker with abilities to save, complete, edit & delete todos.
		</p>
	</div>
</template>

<style lang="scss" scoped>
.about {
	margin: 2rem auto;
	flex-direction: column;
	gap: 2rem;
	max-width: 800px;
	width: 80%;
	min-height: 100vh;
	display: flex;
	align-items: center;

	p {
		line-height: 1.5;
		text-align: justify;
	}
}
</style>
