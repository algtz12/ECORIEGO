<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ECORIEGO</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: space-around;
            background-color: #333;
            padding: 1em;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 1em;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 2em;
        }
        .login-form {
            max-width: 400px;
            margin: 2em auto;
            padding: 2em;
            background-color: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .login-form input {
            width: 100%;
            padding: 1em;
            margin: 1em 0;
            border: 1px solid #ccc;
        }
        .login-form button {
            width: 100%;
            padding: 1em;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        .login-form button:hover {
            background-color: #45a049;
        }
        footer {
            text-align: center;
            padding: 1em;
            background-color: #333;
            color: white;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>ECORIEGO</h1>
    <p>Sistema inteligente de riego automatizado</p>
</header>





<div class="container">
    <div class="login-form">
        <h2>Login</h2>
        <form action="inicio.html">
            <input type="text" placeholder="Usuario" required>
            <input type="password" placeholder="Contraseña" required>
            <button type="submit">Iniciar Sesión</button>
        </form>
    </div>
</div>



</body>

</html>
