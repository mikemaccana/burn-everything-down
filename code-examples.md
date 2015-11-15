.login {
	background-color: whitesmoke;
	button {
		border: 1px solid #222;
		&.active {
			border-color: green;
		}
	}
}

<div class="login">
	<button class="active">Login</button>
</div>




p Structure of elements recreated in class names


<div class="login">
	<button class="login__button--active">Login</button>
</div>

.login {
	background-color: whitesmoke;
}

.login__button {
	border: 1px solid #222;
}

.login__button--active {
	border-color: green;
}           //- Bootstrap example
