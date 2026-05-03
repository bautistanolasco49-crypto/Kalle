<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KALLE</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;900&display=swap" rel="stylesheet">
<style>
body {
  margin: 0;
  font-family: 'Montserrat', sans-serif;
  background: #0B0B0B;
  color: #F5F5F5;
}

header {
  display: flex;
  justify-content: space-between;
  padding: 20px;
}

.logo {
  font-weight: 900;
  font-size: 24px;
}

.hero {
  height: 90vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  flex-direction: column;
}

.hero h1 {
  font-size: 60px;
  margin: 0;
}

.hero p {
  font-size: 20px;
  color: #aaa;
}

.hero span {
  color: #2D5BFF;
}

.btn {
  margin-top: 20px;
  padding: 15px 30px;
  border: 1px solid #2D5BFF;
  color: #2D5BFF;
  text-decoration: none;
  transition: 0.3s;
}

.btn:hover {
  background: #2D5BFF;
  color: white;
}

.section {
  padding: 60px 20px;
  text-align: center;
}

.boxes {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.box {
  border: 1px solid #333;
  padding: 20px;
  width: 250px;
}

footer {
  text-align: center;
  padding: 20px;
  color: #777;
}
</style>
</head>

<body>

<header>
  <div class="logo">KALLE</div>
</header>

<section class="hero">
  <h1>KALLE</h1>
  <p>Hecho para la calle. Pensado para <span>destacar</span>.</p>
  <a href="https://wa.me/549XXXXXXXXXX" class="btn">Acceso anticipado</a>
</section>

<section class="section">
  <h2>Nuestra identidad</h2>
  <p>KALLE nace donde la calle y el detalle se cruzan. No es tendencia. Es criterio.</p>
</section>

<section class="section">
  <h2>Próximamente</h2>
  <p>Drop 01 en camino. Colección limitada.</p>
</section>

<section class="section boxes">
  <div class="box">
    <h3>Exclusividad</h3>
    <p>Colecciones limitadas.</p>
  </div>
  <div class="box">
    <h3>Calidad premium</h3>
    <p>Materiales seleccionados.</p>
  </div>
  <div class="box">
    <h3>Actitud urbana</h3>
    <p>Diseño con identidad.</p>
  </div>
</section>

<footer>
  © 2026 KALLE
</footer>

</body>
</html>
