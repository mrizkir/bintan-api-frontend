<template>
    <div>      
        <v-app-bar dense flat color="primary" dark>
            <v-app-bar-nav-icon></v-app-bar-nav-icon>
            <v-toolbar-title>SIMONEV</v-toolbar-title>
            <v-spacer></v-spacer>
            <v-btn text to="login">Login</v-btn>
        </v-app-bar>
		<v-content>
			<slot />
		</v-content>
		<v-footer color="primary" dark padless fixed>
			<v-col
				class="text-center"
				cols="12"
			>
			{{ new Date().getFullYear() }} — <strong>SIMONEV</strong>
			</v-col>
		</v-footer>
    </div>
</template>