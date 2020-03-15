<template>
	<v-app>
		<nav>
			<v-app-bar dense flat color="#970747" dark>
				<v-app-bar-nav-icon></v-app-bar-nav-icon>
				<v-toolbar-title>SIMONEV</v-toolbar-title>
				<v-spacer></v-spacer>
				<v-btn text to="/">Home</v-btn>
				<v-btn text to="Login">Login</v-btn>
			</v-app-bar>
		</nav>
		<v-content>
			<router-view></router-view>
		</v-content>
		<v-footer color="#970747" dark padless fixed>
			<v-col
				class="text-center"
				cols="12"
			>
			{{ new Date().getFullYear() }} — <strong>SIMONEV</strong>
			</v-col>
		</v-footer>
	</v-app>
</template>
<script>
export default {
	name: "App",

	components: {

	},

	data: () => ({
		//
	})
};
</script>
