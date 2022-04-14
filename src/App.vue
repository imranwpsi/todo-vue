<template>
  <div id="app" class="container">
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style>
* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}
.container {
	padding: 20px;
	max-width: 600px;
	margin: 0 auto;
	text-align: center;
}
</style>
