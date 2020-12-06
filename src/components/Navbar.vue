<template>
	<nav>

		<!-- Navbar -->
		<v-toolbar flat app>
			<v-app-bar-nav-icon @click.stop="drawer = !drawer" class="pink--text"></v-app-bar-nav-icon>
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

		<v-navigation-drawer app class="indigo" v-model="drawer">
			<p>Test</p>
		</v-navigation-drawer>
	</nav>
</template>

<script>
	export default {
		data () {
			return {
				drawer: false
			}
		}
	}
</script>