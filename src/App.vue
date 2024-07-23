<template>

  <div id="app">
		<nav>
			<NavLink />
			<a href="/about">À propos</a>
			<a href="/contact">Contact</a>
		</nav>
		<p>Bienvenue sur notre page d'<NavLink /></p>
    <FooterNav />
	</div>
</template>

<script>
import NavLink from './components/NavLink.vue'
import FooterNav from './components/FooterNav.vue'

export default {
  name: 'App',
  components: {
    NavLink,
    FooterNav
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
