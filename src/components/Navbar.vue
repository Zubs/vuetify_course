<template>
	<nav>
		<v-toolbar flat app>
			<v-toolbar-title>
				<span class="font-weight-light pink--text">AgbaDev</span>
				<span class="text-uppercase blue--text text--lighten-3">Vuetify</span>
			</v-toolbar-title>
			<v-spacer></v-spacer>
			<v-btn color="pink" outlined>
				<span>Logout</span>
				<v-icon right>mdi-exit-to-app</v-icon>
			</v-btn>
		</v-toolbar>
	</nav>
</template>

<script>
	export default {
		name: "Navbar"
	}
</script>