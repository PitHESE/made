<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Titolo Pagina</title>
	<meta name="author" content="Nome Cognome">
	<meta name="copyright" content="2023">
	<meta name="description" content="Titolo Pagina: descrizione">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<style>
		body {
			margin: 2em 1em;
		}
		section {
			display: block;
			border-top: 1px solid white;
		}
		p {
			margin: 0;
		}
		h3 {
			margin: 0;
		}
		.contenuto {
			max-width: 40em;
			padding-left: 1em;
		}
		.testata {
			color: white;
			display: block;
			background-color: rgb(0, 0, 0);
			height: 2em;
			cursor: pointer;
			padding: 0 0 0 1em;
		}
		.chiuso {
			display: none;
		}
	</style>
</head>
<body>

	<section>
		<h3 class="testata">Sezione A</h3>
		<div class="contenuto chiuso">
			<p>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sut in culpa qui officia deserunt mollit anim id est laborum.<br>
			Or incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariaatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.<br>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. isi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.<br>
			</p>
		</div>
	</section>

	<section>
		<h3 class="testata">Sezione B</h3>
		<div class="contenuto chiuso">
			<p>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sut in culpa qui officia deserunt mollit anim id est laborum.<br>
			Or incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariaatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.<br>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. isi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.<br>
			</p>
		</div>
	</section>

	<section>
		<h3 class="testata">Sezione C</h3>
		<div class="contenuto chiuso">
			<p>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sut in culpa qui officia deserunt mollit anim id est laborum.<br>
			Or incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariaatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.<br>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. isi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.<br>
			</p>
		</div>
	</section>

	<section>
		<h3 class="testata">Sezione D</h3>
		<div class="contenuto chiuso">
			<p>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sut in culpa qui officia deserunt mollit anim id est laborum.<br>
			Or incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariaatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.<br>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. isi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.<br>
			</p>
		</div>
	</section>

	<script>
		document.querySelectorAll(".testata").forEach( el => {
			el.addEventListener('click', evt => {
				evt.target.nextElementSibling.classList.toggle("chiuso")
			})
		})
	</script>
</body>