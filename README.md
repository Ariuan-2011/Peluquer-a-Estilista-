<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Peluquería Estilista</title>
  <style>
    :root {
      --marron-claro: #b08968;
      --crema: #fcebd5;
      --gris-claro: #eaeaea;
    }

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: var(--crema);
      color: #333;
    }

    header, footer {
      background-color: var(--marron-claro);
      color: white;
      text-align: center;
      padding: 1.5em;
    }

    nav {
      background-color: var(--gris-claro);
      padding: 1em;
      text-align: center;
    }

    nav a {
      margin: 0 1em;
      color: var(--marron-claro);
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 2em;
    }

    form input, form textarea {
      display: block;
      margin: 0.5em 0;
      width: 100%;
      padding: 0.5em;
      border: 1px solid var(--gris-claro);
      border-radius: 5px;
    }

    .galeria {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }

    .galeria img {
      width: 200px;
      margin: 1em;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>

<header>
  <h1>Estilo Único</h1>
</header>

<nav>
  <a href="#inicio">Inicio</a>
  <a href="#servicios">Servicios</a>
  <a href="#hombres">Hombres</a>
  <a href="#mujeres">Mujeres</a>
  <a href="#galeria">Galería</a>
  <a href="#reservas">Reservas</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="inicio">
  <h2>Inicio</h2>
  <p>¡Bienvenidos! Soy Mariana, estilista profesional con más de 10 años de experiencia en el mundo de la belleza. Desde mi salón, ubicado en el corazón de Montevideo, busco brindarte una atención personalizada, con servicios de alta calidad y un ambiente cálido. Mi objetivo es ayudarte a encontrar tu estilo ideal, resaltando lo mejor de vos mismo o vos misma. Trabajo con productos de primera línea y me capacito constantemente para ofrecerte las últimas tendencias en cortes, coloraciones y tratamientos, tanto para mujeres como para hombres.</p>
</section>

<section id="servicios">
  <h2>Servicios Generales</h2>
  <p>Ofrecemos una variedad de servicios profesionales adaptados a todos los gustos, estilos y géneros. Entre ellos:</p>
  <ul>
    <li><strong>Cortes clásicos:</strong> estilos tradicionales para quienes prefieren lo atemporal.</li>
    <li><strong>Cortes modernos:</strong> tendencias actuales como el pixie, bob, mullet o fade.</li>
    <li><strong>Mechas:</strong> balayage, californianas, highlights y babylights para iluminar el cabello.</li>
    <li><strong>Baños de color:</strong> tonalidades suaves que reavivan el cabello sin dañarlo.</li>
    <li><strong>Tintes:</strong> opciones permanentes o semipermanentes para todos los estilos.</li>
    <li><strong>Tratamientos de hidratación:</strong> botox capilar y baños de crema para restaurar el brillo.</li>
    <li><strong>Alisados:</strong> taninoplastia o alisado japonés para un cabello liso y saludable.</li>
  </ul>
</section>

<section id="hombres">
  <h2>Servicios para Hombres</h2>
  <ul>
    <li><strong>Cortes clásicos:</strong> estilos tradicionales como el corte recto o militar, ideales para un look limpio y profesional.</li>
    <li><strong>Cortes modernos:</strong> tendencias como el fade, undercut y estilos con diseño personalizados.</li>
    <li><strong>Mechas y coloraciones:</strong> opciones discretas o audaces como reflejos y tonos platinados.</li>
    <li><strong>Baños de color:</strong> para realzar el tono natural del cabello sin un cambio permanente.</li>
    <li><strong>Tintes permanentes:</strong> para cubrir canas o cambiar completamente el look.</li>
    <li><strong>Tratamientos de hidratación:</strong> como baños de crema y botox capilar para fortalecer el cabello.</li>
    <li><strong>Alisados:</strong> taninoplastia o alisado japonés para controlar el volumen y el frizz.</li>
  </ul>
</section>

<section id="mujeres">
  <h2>Servicios para Mujeres</h2>
  <ul>
    <li><strong>Cortes clásicos:</strong> estilos como recto, en capas o long bob para un look sofisticado y elegante.</li>
    <li><strong>Cortes modernos:</strong> cortes pixie, shaggy, mullet o bob invertido, ideales para renovar el estilo.</li>
    <li><strong>Mechas:</strong> balayage, californianas, babylights y highlights para iluminar el rostro y dar dimensión.</li>
    <li><strong>Baños de color:</strong> tonos suaves y brillantes que revitalizan el color sin dañar el cabello.</li>
    <li><strong>Tintes permanentes y semipermanentes:</strong> para lograr colores vibrantes, coberturas completas o tonos fantasía.</li>
    <li><strong>Tratamientos hidratantes:</strong> botox capilar, keratina y baños de crema para recuperar el brillo y la suavidad.</li>
    <li><strong>Técnicas de alisado:</strong> como el alisado japonés o la taninoplastia para un acabado liso y duradero.</li>
  </ul>
</section>

<section id="galeria">
  <h2>Galería</h2>
  <div class="galeria">
    <img src="https://www.nuevamujer.com/resizer/v2/M2WL63MKPRFY3IPYKWPRSWJ64M.jpg?auth=83428d035f321c3f7c2c4b72384606061ff4a50dd1c83e452d61122b2925280c&width=800&height=1200" alt="Mujeres">
    <img src="https://content.clara.es/medio/2024/12/12/mullet_da3bda6e_241212145520_736x736.webp" alt="Mujeres">
    <img src="https://i.pinimg.com/736x/7c/5d/3c/7c5d3cad9f403188d790e6e7c26a7551.jpg" alt="Mujeres">
    <img src="https://i.pinimg.com/736x/98/86/71/9886711ceaa1e7c209cc7bffe44d2967.jpg" alt="Mujeres">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRx8DkU7PNQCq6iADqUZZqPM58vHb5Ev42aMg&s" alt="Hombres">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQYmiZWn5lQlJl7uViXpBTgbd-KEqbs1TgNKg&s" alt="Hombres">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSYy2nqzVHjJbgPvkIZTzerHDqGCLZslJM8EQ&s" alt="Hombres">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQY1hdzr3PDBCP2alnmD1ZIyF7mEsWiiRolOw&s" alt="Hombres">
  </div>
</section>

<section id="reservas">
  <h2>Reservas</h2>
  <p>Hacé tu reserva completando el siguiente formulario:</p>
  <p><a href="https://docs.google.com/forms/d/e/1FAIpQLSfjEbc2AXMbe-YviV_4LuF9AUqlewa8tTr_gd3W8bWOS5ACrA/viewform?usp=pp_url" target="_blank">Formulario de Reserva</a></p>
  <p>También podés hacer tu reserva vía WhatsApp al <a href="https://wa.me/59892916210" target="_blank">+598 92 916 210</a>.</p>
</section>

<section id="contacto">
  <h2>Contacto</h2>
  <p>📍 Dirección: Bulevar Artigas 2456, Montevideo, Uruguay</p>
  <p>📞 Teléfono: +598 92 916 210</p>
  <p>📧 Correo: arianatacuabe3@gmail.com</p>
</section>

<footer>
  <p>&copy; 2025 Peluquería Estilista - Todos los derechos reservados</p>
</footer>

</body>
</html>
