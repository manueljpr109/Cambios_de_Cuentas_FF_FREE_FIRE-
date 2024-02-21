<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Inicio de sesión para gamers</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>¡Bienvenido a tu zona de batalla!</h1>
  </header>
  <main>
    <section class="imagenes">
      <img src="imagenes/freefire.jpg" alt="Free Fire">
      <img src="imagenes/callofduty.jpg" alt="Call of Duty">
      <img src="imagenes/pubg.jpg" alt="PUBG">
      <img src="imagenes/fortnite.jpg" alt="Fortnite">
    </section>
    <section class="formulario">
      <h2>Inicia sesión y únete a la comunidad</h2>
      <form action="#">
        <label for="usuario">Usuario:</label>
        <input type="text" id="usuario" name="usuario">
        <label for="contrasena">Contraseña:</label>
        <input type="password" id="contrasena" name="contrasena">
        <a href="#">¿Olvidaste tu contraseña?</a>
        <button type="submit">¡Inicia sesión y juega!</button>
      </form>
    </section>
    <section class="opciones">
      <p>¿Eres nuevo? <a href="#">Regístrate aquí</a></p>
      <p>¿Necesitas ayuda? <a href="#">Visita nuestro centro de ayuda</a></p>
    </section>
  </main>
  <script src="script.js"></script>
</body>
</html>
