<template>
	<div class="wtf">
		<h1>{{ msg }}</h1>
		<img :src="img" alt="pic" />
	</div>
</template>

<script>
export default {
	name: "Fuck",
	props: {
		msg: String,
		img: String,
	},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
	margin: 40px 0 0;
}
ul {
	list-style-type: none;
	padding: 0;
}
li {
	display: inline-block;
	margin: 0 10px;
}
a {
	color: #42b983;
}
#wtf {
background-size: cover;
background-position: center;
height: 500;
width: 500;
}
</style>
