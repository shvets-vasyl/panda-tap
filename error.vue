<template>
  <div>
    <ClientOnly>
      <main class="error">
				<div class="h2">Error Getting Data</div>
				<div class="h2">Try Again Later</div>
			</main>
		</ClientOnly>
	</div>
</template>

<script setup lang="ts"></script>

<style lang="scss" scoped>
.error {
  height: 100vh;
	display: flex;
	align-items: center;
	justify-content: center;
	flex-direction: column;
}
</style>
