<html>
    <head>
        <meta charset="utf-8" />
        <link rel="stylesheet" href="style.css" />
        <title>- Mon Formulaire -</title>
    </head>

    <body>
		<p>
			Cette page ne contient que du HTML.<br />
			Veuillez taper votre prénom :
		</p>

		<form action="cible.php" method="post">
			<p>
				<input type="text" name="prenom"/>
				<input type="submit" value="Valider" />
			</p>
		</form>
		<p>Et maintenant votre mot de passe:</p>
			<p><form action="cible2.php" method="post">
				<input type="text" password="password" />
				<input type="submit" value="Valider" />
			</p>
		</form>
    </body>
</html>