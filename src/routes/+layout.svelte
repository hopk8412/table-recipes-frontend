<!-- <div> -->
	<nav>
		<a href="/" class="nav-item">Home</a>
		<a href="/recipes" class="nav-item">About</a>
		<a href="/login" class="nav-item login">Log In</a>
	</nav>
<!-- </div> -->

<slot />

<style>
    @font-face {
        font-family: 'Rodin';
        src: local(''), url('/fonts/FOTRodin%20Pro%20DB.otf') format('opentype');
    }
	nav {
		background-color: #005A9C;
        margin: 20px;
        border-radius: 10px;
        display: flex;
        flex-wrap: wrap;
        justify-content: right;
	}
    .nav-item {
        color: white;
        margin: 15px;
    }

    .login {
        right: 0;
    }

    * {
    font-family: 'Rodin', 'Helvetica Neue', sans-serif;
}
</style>
