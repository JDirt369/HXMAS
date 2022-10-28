<!DOCTYPE html>
<html>
	<head>
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<style>
			h1 {
				font-family: Georgia, serif;
				color: #bb27de;
				text-align: Center;
			}
			p {
				font-family: Arial, sans-serif;
				font-size: 14px;
				text-align: default;
				color: #2f2d2d;
			}
		</style>
	</head>
	<body>
		<h1>CLAIM YOUR FREE HXMS BELOW!!
               </h1>
		<p></p>
	</body>
</html>

<main>


<slot />
</main>

<footer>
	<p>visit <a href="https://Hex.com">HEX.COM</a> to learn about HEX</p>
</footer>

<style>
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 1024px;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 40px;
	}

	footer a {
		font-weight: bold;
	}

	@media (min-width: 480px) {
		footer {
			padding: 40px 0;
		}
	}
</style>
