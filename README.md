# comidas-saludables
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Recetas Saludables para Niños</title>
  <style>
    /* Estilos generales */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0; padding: 0;
      background: #f7f9fc;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 1rem 2rem;
      position: fixed;
      width: 100%;
      top: 0; left: 0;
      z-index: 1000;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    header h1 {
      margin: 0;
      font-weight: 700;
      font-size: 1.8rem;
    }
    nav {
      margin-top: 0.5rem;
    }
    nav a {
      color: white;
      margin-right: 1.2rem;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #c8e6c9;
    }
    main {
      max-width: 900px;
      margin: 100px auto 40px;
      padding: 0 1rem;
    }
    section {
      margin-bottom: 3rem;
      padding-bottom: 2rem;
      border-bottom: 1px solid #ddd;
    }
    h2 {
      color: #4CAF50;
      margin-bottom: 0.8rem;
      border-bottom: 3px solid #81c784;
      display: inline-block;
      padding-bottom: 0.3rem;
    }
    .recipe {
      background: white;
      padding: 1rem 1.5rem;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      margin-bottom: 1.5rem;
      transition: transform 0.3s ease;
    }
    .recipe:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.15);
    }
    .ingredients, .preparation, .benefits {
      margin-top: 0.5rem;
    }
    .ingredients ul {
      list-style: disc inside;
      margin: 0.3rem 0 1rem 0;
      padding-left: 1rem;
    }
    iframe {
      width: 100%;
      height: 300px;
      border-radius: 8px;
      border: none;
      margin-top: 1rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    iframe:hover {
      transform: scale(1.02);
    }
    footer {
      text-align: center;
      padding: 1.5rem 0;
      background: #4CAF50;
      color: white;
      font-weight: 600;
      margin-top: 3rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Recetas Saludables para Niños</h1>
  <nav>
    <a href="#dulces">Dulces</a>
    <a href="#salados">Salados</a>
    <a href="#picantes">Picantes</a>
  </nav>
</header>

<main>
  <section id="dulces">
    <h2>🍌 Recetas Dulces Saludables</h2>
    <article class="recipe">
      <h3>Galletas de avena y manzana</h3>
      <div class="ingredients">
        <strong>Ingredientes:</strong>
        <ul>
          <li>1 taza de avena en hojuelas</li>
          <li>1 manzana</li>
          <li>1 huevo</li>
          <li>1/2 cucharadita de canela</li>
        </ul>
      </div>
      <div class="preparation">
        <strong>Preparación:</strong>
        <p>Precalienta el horno a 180°C y forra una bandeja con papel pergamino. Ralla la manzana y mezcla con la avena, el huevo y la canela. Forma pequeñas bolitas con la mezcla y colócalas en la bandeja. Hornea durante 15-20 minutos o hasta que estén doradas.</p>
      </div>
      <div class="benefits">
        <strong>Beneficios:</strong> Estas galletas son ricas en fibra y antioxidantes, ideales para una merienda saludable.
      </div>
      <iframe src="https://www.youtube.com/embed/z9ov3C7XM3o" allowfullscreen></iframe>
    </article>
    <!-- Aquí puedes agregar más recetas dulces -->
  </section>

  <section id="salados">
    <h2>🥕 Recetas Saladas Saludables</h2>
    <article class="recipe">
      <h3>Hummus casero con palitos de verduras</h3>
      <div class="ingredients">
        <strong>Ingredientes:</strong>
        <ul>
          <li>1 taza de garbanzos cocidos</li>
          <li>2 cucharadas de tahini (pasta de sésamo)</li>
          <li>Jugo de 1 limón</li>
          <li>1 diente de ajo</li>
          <li>2 cucharadas de aceite de oliva</li>
          <li>Sal al gusto</li>
          <li>Verduras variadas (zanahorias, pepinos, apio)</li>
        </ul>
      </div>
      <div class="preparation">
        <strong>Preparación:</strong>
        <p>En una licuadora o procesador de alimentos, mezcla los garbanzos, tahini, jugo de limón, ajo y aceite de oliva hasta obtener una pasta suave. Si es necesario, añade un poco de agua para ajustar la consistencia. Lava y corta las verduras en palitos. Sirve el hummus en un bol acompañado de los palitos de verduras.</p>
      </div>
      <div class="benefits">
        <strong>Beneficios:</strong> El hummus es rico en proteínas vegetales y fibra, y las verduras aportan vitaminas esenciales.
      </div>
      <iframe src="https://www.youtube.com/embed/VuTis6DmIME" allowfullscreen></iframe>
    </article>
    <!-- Más recetas saladas aquí -->
  </section>

  <section id="picantes">
    <h2>🌶 Recetas Picantes para Pequeños Aventureros</h2>
    <article class="recipe">
      <h3>Tostadas de tomate y albahaca</h3>
      <div class="ingredients">
        <strong>Ingredientes:</strong>
        <ul>
          <li>4 rebanadas de pan integral</li>
          <li>2 tomates maduros</li>
          <li>Hojas de albahaca fresca</li>
          <li>Aceite de oliva</li>
          <li>Sal y pimienta al gusto</li>
        </ul>
      </div>
      <div class="preparation">
        <strong>Preparación:</strong>
        <p>Tuesta las rebanadas de pan integral. Lava y corta los tomates en rodajas finas. Lava las hojas de albahaca. Coloca las rodajas de tomate sobre las tostadas. Añade las hojas de albahaca encima. Rocía con un poco de aceite de oliva y sazona con sal y pimienta al gusto.</p>
      </div>
      <div class="benefits">
        <strong>Beneficios:</strong> Esta receta es rica en antioxidantes y fibra, ideal como aperitivo saludable.
      </div>
      <iframe src="https://www.youtube.com/embed/1_mKLRtdjgQ" allowfullscreen></iframe>
    </article>
    <!-- Más recetas picantes aquí -->
  </section>
</main>

<footer>
  &copy; 2025 Recetas Saludables para Niños | Creado con 💚 por Ti y ChatGPT
</footer>

</body>
</html>
