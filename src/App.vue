<template>

  <div id="app">
		<nav>
			<NavLink url="/" text="Accueil" />
      <NavLink url="/about" text="A propos" />
      <NavLink url="/portfolio" text="Portfolio" />
		</nav>
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

</style>
