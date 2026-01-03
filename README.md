<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Davah Inmobiliaria</title>
  <meta name="description" content="Davah Inmobiliaria. Soluciones patrimoniales sólidas con un enfoque profesional, transparente y confiable." />

  <!-- Tipografía (fallback a Commuters Sans Light) -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500&display=swap" rel="stylesheet">

  <style>
    :root {
      --azul-davah: #161e35;
      --gris-claro: #c2c1c1;
      --gris-fondo: #efefef;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Montserrat', Arial, sans-serif;
      background-color: var(--gris-fondo);
      color: var(--azul-davah);
      line-height: 1.6;
    }

    header {
      background-color: #ffffff;
      padding: 30px 10%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid var(--gris-claro);
    }

    header h1 {
      font-weight: 400;
      font-size: 26px;
      letter-spacing: 1px;
    }

    nav a {
      margin-left: 25px;
      text-decoration: none;
      color: var(--azul-davah);
      font-size: 14px;
    }

    .hero {
      padding: 90px 10%;
      background-color: #ffffff;
    }

    .hero h2 {
      font-weight: 300;
      font-size: 38px;
      max-width: 700px;
    }

    .hero p {
      margin-top: 20px;
      max-width: 600px;
      color: #555;
    }

    .section {
      padding: 80px 10%;
    }

    .section h3 {
      font-weight: 400;
      font-size: 28px;
      margin-bottom: 30px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 40px;
    }

    .card {
      background-color: #ffffff;
      padding: 35px;
      border: 1px solid var(--gris-claro);
    }

    .card h4 {
      font-weight: 500;
      margin-bottom: 15px;
    }

    .card p {
      font-size: 14px;
      color: #555;
    }

    .contact {
      background-color: #ffffff;
      padding: 80px 10%;
      border-top: 1px solid var(--gris-claro);
    }

    .contact p {
      margin-bottom: 10px;
    }

    footer {
      background-color: var(--azul-davah);
      color: #ffffff;
      padding: 30px 10%;
      font-size: 12px;
    }

    footer p {
      max-width: 800px;
    }

    @media (max-width: 768px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }

      nav {
        margin-top: 15px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Davah Inmobiliaria</h1>
    <nav>
      <a href="#nosotros">Nosotros</a>
      <a href="#servicios">Servicios</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Soluciones patrimoniales sólidas con un enfoque profesional y transparente</h2>
    <p>
      En Davah Inmobiliaria acompañamos a nuestros clientes en cada etapa de su proceso inmobiliario, brindando asesoría integral, confidencialidad y certeza jurídica.
    </p>
  </section>

  <section class="section" id="nosotros">
    <h3>Nosotros</h3>
    <p>
      Davah Inmobiliaria es una empresa orientada a la generación de valor patrimonial, basada en principios de profesionalismo, ética, confidencialidad y transparencia. Nuestro compromiso es ofrecer soluciones inmobiliarias confiables y personalizadas.
    </p>
  </section>

  <section class="section" id="servicios">
    <h3>Servicios</h3>
    <div class="grid">
      <div class="card">
        <h4>Asesoría Inmobiliaria</h4>
        <p>Orientación profesional para la compra, venta y arrendamiento de bienes inmuebles.</p>
      </div>
      <div class="card">
        <h4>Cotizaciones y Presupuestos</h4>
        <p>Elaboración de propuestas claras, detalladas y alineadas a sus necesidades patrimoniales.</p>
      </div>
      <div class="card">
        <h4>Gestión Documental</h4>
        <p>Administración de contratos, pedimentos, facturación y documentación relacionada.</p>
      </div>
      <div class="card">
        <h4>Acompañamiento Legal</h4>
        <p>Procesos respaldados por buenas prácticas y apego a la normatividad vigente.</p>
      </div>
    </div>
  </section>

  <section class="contact" id="contacto">
    <h3>Contacto</h3>
    <p><strong>Damián Vázquez</strong></p>
    <p>Director Comercial</p>
    <p>Tel. 55 4090 8446</p>
    <p>Correo: dvazquez@davahinmobiliaria.com</p>
    <p>Instagram: @davahinmobiliaria</p>
    <p>www.davahinmobiliaria.com</p>
  </section>

  <footer>
    <p>
      La información contenida en este sitio es confidencial y se encuentra protegida conforme a la Ley Federal de Protección de Datos Personales en Posesión de los Particulares. Davah Inmobiliaria no autoriza la divulgación de información a terceros.
    </p>
  </footer>

</body>
</html>


<!--
**DavahInmobiliaria/DavahInmobiliaria** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
