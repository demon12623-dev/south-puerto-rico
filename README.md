<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>TrapStarz</title>

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;800&display=swap" rel="stylesheet">

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Montserrat', sans-serif;
  min-height: 100vh;
  background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.85)),
  url('ChatGPT Image 28 ene 2026, 20_32_59.png') no-repeat center center/cover;
  color: #fff;
  overflow-x: hidden;
}

/* HEADER */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 40px;
}

.title-box {
  display: flex;
  flex-direction: column;
}

header h1 {
  font-size: 1.5rem;
  font-weight: 800;
  color: #ff2a2a;
  text-shadow: 0 0 10px #ff2a2a;
}

/* 🔥 FUNDADORES DEBAJO DEL NOMBRE */
.founders {
  font-size: 0.75rem;
  color: #aaa;
  margin-top: 4px;
}

.founders span {
  color: #ff2a2a;
  font-weight: 700;
  text-shadow: 0 0 8px #ff2a2a;
}

/* NAV */
nav a {
  margin: 0 12px;
  text-decoration: none;
  color: #ddd;
  font-weight: 500;
}

.btn {
  background: #ff2a2a;
  color: #000;
  padding: 10px 18px;
  border-radius: 10px;
  text-decoration: none;
  font-weight: 700;
  box-shadow: 0 0 15px rgba(255,42,42,0.8);
}

/* HERO */
.hero {
  text-align: center;
  padding: 120px 20px 60px;
  max-width: 900px;
  margin: auto;
}

.logo {
  max-width: 500px;
  margin: 0 auto 30px;
  animation: float 3s ease-in-out infinite, glow 2s ease-in-out infinite alternate;
}

@keyframes float {
  0% { transform: translateY(0px); }
  50% { transform: translateY(-15px); }
  100% { transform: translateY(0px); }
}

@keyframes glow {
  from { filter: drop-shadow(0 0 10px #ff0000); }
  to { filter: drop-shadow(0 0 30px #ff0000); }
}

.hero p {
  color: #ccc;
  margin-bottom: 40px;
  line-height: 1.6;
}

.actions a {
  margin: 10px;
  padding: 14px 26px;
  border-radius: 14px;
  font-weight: 700;
  text-decoration: none;
  display: inline-block;
}

.btn-outline {
  border: 2px solid #ff2a2a;
  color: #ff2a2a;
  box-shadow: 0 0 10px rgba(255,42,42,0.7);
}

/* SECCIONES */
.info, .projects {
  background: rgba(0,0,0,0.6);
  margin: 60px auto;
  padding: 40px;
  border-radius: 20px;
  max-width: 900px;
  text-align: center;
  backdrop-filter: blur(6px);
}

.projects h3 {
  margin-bottom: 20px;
  font-size: 2rem;
  color: #ff2a2a;
}

.projects ul {
  list-style: none;
}

.projects li {
  margin: 10px 0;
}

/* BOTONES FLOTANTES */
.discord-float {
  position: fixed;
  bottom: 20px;
  left: 20px;
  background: #5865F2;
  color: #fff;
  padding: 14px 18px;
  border-radius: 50px;
  text-decoration: none;
  font-weight: 700;
  box-shadow: 0 0 20px rgba(88,101,242,0.8);
}

.contact-float {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #00c853;
  color: #000;
  padding: 14px 18px;
  border-radius: 50px;
  font-weight: 700;
  text-decoration: none;
  box-shadow: 0 0 20px rgba(0,200,83,0.9);
}
</style>
</head>

<body>

<header>
<div class="title-box">
  <h1>TrapStarz</h1>
  <div class="founders">
    Fundadores: <span>anonrlc_dev & y3zzy</span>
  </div>
</div>

<nav>
<a href="#">Inicio</a>
<a href="#info">Sobre</a>
<a href="#">Equipo</a>
<a href="#">Comunidad</a>
<a class="btn" href="https://discord.gg/fTpBeG8YHU" target="_blank">Únete</a>
</nav>
</header>

<section class="hero">
<img src="ChatGPT Image 28 ene 2026, 20_32_59.png" class="logo">
<p>
La experiencia definitiva de Roleplay urbano. Cada decisión cuenta, cada movimiento crea tu leyenda.
</p>

<div class="actions">
<a href="#info" class="btn">Descubre Más</a>
<a href="https://discord.gg/fTpBeG8YHU" target="_blank" class="btn-outline">Únete Ahora</a>
</div>
</section>

<!-- ✅ ESTA PARTE ERA LA QUE FALTABA -->
<section id="info" class="info">
<h3>¿Qué hacemos en TrapStarz?</h3>
<p>
• Vendemos carros personalizados y exclusivos.<br><br>
• Creamos mapas únicos desde cero.<br><br>
• Vendemos sistemas avanzados para servidores RP.<br><br>
• Tenemos otros proyectos hechos desde cero como <b>South Puerto Rico</b> y <b>TrapStarz RP</b>.
</p>
</section>

<section class="projects">
<h3>Proyectos</h3>
<ul>
<li>🔥 TrapStarz RP</li>
<li>🌴 South Puerto Rico</li>
<li>🚗 Sistemas de carros exclusivos</li>
<li>🗺️ Mapas personalizados desde cero</li>
</ul>
</section>

<audio autoplay loop>
<source src="music.mp3" type="audio/mpeg">
</audio>

<a href="https://discord.gg/fTpBeG8YHU" target="_blank" class="discord-float">Discord</a>

<a href="tel:+19393633205"
   class="contact-float"
   onclick="alert('📱 939-363-3205\nContáctanos por cualquier asunto o por Discord');">
Contáctanos
</a>

</body>
</html>
