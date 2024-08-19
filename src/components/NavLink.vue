<script>
export default {
	name: 'NavLink',
	props : ['url', 'text']
}
</script>

<template>
	<a :href="url">{{ text }}</a> 
</template>

<style>
	a {
        padding-right: 5%;
	}
</style>