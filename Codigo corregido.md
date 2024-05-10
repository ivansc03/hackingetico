# Codigo corregido 

# Índice

1. [Register_player](#Register-player)
2. [## /private/auth.php](#/private/auth.php)

## Register_player
``` <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="css/style.css">
    <title>Práctica RA3 - Players list</title>
</head>
<body>
<header>
    <h1>Player</h1>
</header>
<main class="player">
    <form action="#" method="post">
        <input type="hidden" name="id" value=""><br>
        <h3>Player name</h3>
        <textarea name="name"></textarea><br>
        <h3>Team name</h3>
        <textarea name="team"><?php echo $team; ?></textarea><br>
        <input type="submit" value="Send">
    </form>
    <form action="#" method="post" class="menu-form">
        <a href="index.php">Back to home</a>
        <a href="list_players.php">Back to list</a>
        <input type="submit" name="Logout" value="Logout" class="logout">
    </form>
</main>
<footer class="listado">
    <img src="images/logo-iesra-cadiz-color-blanco.png" alt="Logo IES Ra Cadiz">
    <h4>Puesta en producción segura</h4>
    <p>Please <a href="http://www.donate.co?amount=100&amp;destination=ACMEScouting/"> donate</a> </p>
</footer>
</body>
</html>


## /private/auth.php

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="css/style.css">
    <title>Práctica RA3 - Authentication page</title>
</head>
<body>
<header class="auth">
    <h1>Authentication page</h1>
</header>
<section class="auth">
    <div class="message">
        Invalid user or password.<br>
    </div>
    <section>
        <div>
            <h2>Login</h2>
            <form action="#" method="post">
                <label for="username">User</label>
                <input type="text" id="username" name="username"><br>
                <label for="password">Password</label>
                <input type="password" id="password" name="password"><br>
                <input type="submit" value="Login">
            </form>
        </div>

        <div>
            <h2>Logout</h2>
            <form action="#" method="post">
                <input type="submit" name="Logout" value="Logout">
            </form>
        </div>
    </section>
</section>
<footer>
    <h4>Puesta en producción segura</h4>
    <p>Please <a href="http://www.donate.co?amount=100&amp;destination=ACMEScouting/"> donate</a> </p>
</footer>
</body>
</html>




