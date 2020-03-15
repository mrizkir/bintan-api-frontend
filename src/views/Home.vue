<template>
	<v-container>
		<v-row class="text-center">
			<v-col cols="12">
				<v-img
					:src="require('../assets/logo.svg')"
					class="my-3"
					contain
					height="200"
				/>
			</v-col>
			<v-col class="mb-4">
				<h1 class="display-2 font-weight-bold mb-3">
					BINTAN API
				</h1>

				<p class="subheading font-weight-regular">
					Bintan API (Application Programming Interface) menyediakan berbagai macam web service untuk dikonsumsi. 
					<br>Cek di  
					<a
						href="https:/github.com/mrizkir/bintan-api"
						target="_blank"
					>github</a>
				</p>
			</v-col>
		</v-row>
	</v-container>
</template>
<script>
export default {
	name: 'Home',    
  }
</script>
<style scoped>
h1 {
	color:#970747
}
p {
	color:#970747
}
</style>