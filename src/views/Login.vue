<template>
	<v-content>
		<v-container class="fill-height" fluid>
			<v-row align="center" justify="center">
				<v-col cols="12" sm="8" md="4">
					<v-card class="elevation-12">
						<v-toolbar color="primary" dark flat>
							<v-toolbar-title>LOGIN</v-toolbar-title>							
						</v-toolbar>
						<v-card-text>
							<v-form>
								<v-text-field label="Login" name="login" prepend-icon="mdi-account-outline" type="text" />
								<v-text-field
									id="password"
									label="Password"
									name="password"
									prepend-icon="mdi-lock"
									type="password"
								/>
							</v-form>
						</v-card-text>
						<v-card-actions>
							<v-spacer />
							<v-btn color="primary" to="/">
								Batal
								<v-icon>
                                    mdi-arrow-left-thick
                                </v-icon>
							</v-btn>
							<v-btn color="primary">
								Login
								<v-icon>
                                    mdi-arrow-right-thick
                                </v-icon>
							</v-btn>							
						</v-card-actions>
					</v-card>
				</v-col>
			</v-row>
		</v-container>
	</v-content>
</template>

<script>
export default {
	name: 'Login',
  }
</script>