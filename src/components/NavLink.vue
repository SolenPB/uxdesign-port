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
		text-decoration: none;
        color: white;
        padding-right: 5%;
	}
</style>