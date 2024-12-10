<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Iniciar Sesión • SAN ONLINE</title>
<link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="container">
    <h1 class="title">SAN ONLINE</h1>
    <form id="loginForm">
        <input type="email" id="email" placeholder="Correo Electrónico" required>
        <input type="password" id="password" placeholder="Contraseña" required>
        <button type="submit">Iniciar Sesión</button>
    </form>
    <div class="separator">o</div>
    <div class="social-buttons">
        <button class="facebook">Iniciar sesión con Facebook</button>
        <button class="google">Iniciar sesión con Google</button>
    </div>
</div>
<script src="script.js"></script>

body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background-color: #00FF00; /* Color de fondo verde fluorescente */
}

.container {
    max-width: 400px;
    margin: 100px auto;
    padding: 20px;
    border-radius: 10px; /* Bordes redondeados */
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Sombra suave para efecto 3D */
    background-color: #fff;
    text-align: center;
}

.title {
    font-size: 24px;
    margin-bottom: 20px;
}


document.getElementById('loginForm').addEventListener('submit', function(event) {
    event.preventDefault();
    // Aquí puedes agregar la lógica para autenticar al usuario con el correo electrónico y contraseña
    // Por ejemplo, puedes enviar los datos a un servidor para verificar las credenciales
});


