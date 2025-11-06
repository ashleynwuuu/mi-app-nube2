<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,
initial-scale=1.0">
<title>Mi App en la Nube</title>
<style>
body {
font-family: Arial, sans-serif;
text-align: center;
margin: 50px;
background-color: #f5f5f5;
}
h1 {
color: #2c3e50;
}
button {
background-color: #ff9900;

3

color: white;
border: none;
padding: 10px 20px;
border-radius: 5px;
cursor: pointer;
font-size: 16px;
margin: 10px;
}
button:hover {
background-color: #e68a00;
}
#mensaje {
margin-top: 20px;
font-size: 18px;
color: #27ae60;
}
</style>
</head>
<body>
<h1>¡Hola desde la Nube! ️</h1>
<p>Esta es mi aplicación desplegada en Netlify.</p>
<button onclick="mostrarMensaje()">Haz clic aquí</button>
<p id="mensaje"></p>
<script>
function mostrarMensaje() {
document.getElementById('mensaje').textContent =
'¡Despliegue exitoso! 🎉';
}
</script>
</body>
2. </html>
