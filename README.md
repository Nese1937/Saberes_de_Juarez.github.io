<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> Saberes Juárez | Web de Saberes Comunitarios </title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <style>
    .hero { 
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1580130684518-8a3f4c2c3c3d?ixlib=rb-4.0.3&auto=format&fit=crop&q=80') center/cover no-repeat;
    }
    .card-hover:hover { transform: translateY(-8px); transition: all 0.3s; }
  </style>
</head>
<body class="bg-gray-50 font-sans">

  <!-- Navbar -->
  <nav class="bg-white shadow-lg sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <div class="flex items-center gap-3">
        <i class="fa-solid fa-leaf text-3xl text-emerald-700"></i>
        <h1 class="text-2xl font-bold text-gray-800">Saberes Juárez</h1>
      </div>
      <div class="hidden md:flex space-x-8 text-lg">
        <a href="#sobre" class="hover:text-emerald-700 transition">Sobre el proyecto</a>
        <a href="#actividades" class="hover:text-emerald-700 transition">Actividades</a>
        <a href="#saberes" class="hover:text-emerald-700 transition">Saberes</a>
        <a href="#galeria" class="hover:text-emerald-700 transition">Galería</a>
      </div>
      <button onclick="alert('¡Gracias por querer contribuir! Pronto habilitaremos esta función.')"
              class="bg-emerald-700 hover:bg-emerald-800 text-white px-6 py-2 rounded-full font-medium">
        Contribuir
      </button>
    </div>
  </nav>

  <!-- Hero -->
  <section class="hero text-white py-32 text-center">
    <div class="max-w-4xl mx-auto px-6">
      <h2 class="text-5xl md:text-6xl font-bold mb-6">Web de Saberes Comunitarios</h2>
      <h3 class="text-3xl mb-8">Ciudad Juárez, Chihuahua</h3>
      <p class="text-xl mb-10 max-w-2xl mx-auto">
        Preservando la memoria viva de nuestra comunidad a través de las voces de nuestros abuelos, artesanos y sabios juarenses.
      </p>
      <a href="#sobre" 
         class="inline-block bg-white text-emerald-800 px-10 py-4 rounded-full text-lg font-semibold hover:bg-emerald-100 transition">
        Conocer el proyecto
      </a>
    </div>
  </section>

  <!-- Sobre el proyecto -->
  <section id="sobre" class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-12 text-gray-800">Nuestro Propósito</h2>
      <div class="grid md:grid-cols-2 gap-12 items-center">
        <div>
          <p class="text-lg leading-relaxed text-gray-700">
            La identidad de Juárez se construye con sus tradiciones y diversidad cultural. Este proyecto se enfoca en la 
            <strong>colaboración, la comunicación y la creación de contenidos digitales</strong> utilizando software libre, 
            con énfasis en la preservación de la cultura local y la integración intergeneracional.
          </p>
          <br>
          <p class="text-lg leading-relaxed text-gray-700">
            Rescatamos, documentamos y difundimos de forma estructurada los saberes, oficios y tradiciones locales 
            que están en riesgo de desaparecer.
          </p>
        </div>
        <div class="rounded-2xl overflow-hidden shadow-xl">
          <img src="https://images.unsplash.com/photo-1580130684518-8a3f4c2c3c3d?ixlib=rb-4.0.3&auto=format&fit=crop&q=80" 
               alt="Cultura Juárez" class="w-full">
        </div>
      </div>
    </div>
  </section>

  <!-- Actividades clave -->
  <section id="actividades" class="py-20 bg-emerald-50">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-12 text-gray-800">Actividades Digitales Clave</h2>
      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
        <div class="bg-white p-8 rounded-2xl shadow-md card-hover">
          <h3 class="font-semibold text-xl mb-4 text-emerald-700">1. Documentación</h3>
          <p class="text-gray-600">Entrevistas a abuelos, artesanos y portadores de saberes para registrar recetas, remedios, historias y tradiciones.</p>
        </div>
        <div class="bg-white p-8 rounded-2xl shadow-md card-hover">
          <h3 class="font-semibold text-xl mb-4 text-emerald-700">2. Recopilación de Riesgo</h3>
          <p class="text-gray-600">Identificamos qué saberes y oficios están en mayor peligro de perderse en Ciudad Juárez.</p>
        </div>
        <div class="bg-white p-8 rounded-2xl shadow-md card-hover">
          <h3 class="font-semibold text-xl mb-4 text-emerald-700">3. Edición Colaborativa</h3>
          <p class="text-gray-600">Usamos herramientas libres (Cryptpad, Riseup Pad, etc.) para redactar y editar juntos los contenidos.</p>
        </div>
        <div class="bg-white p-8 rounded-2xl shadow-md card-hover">
          <h3 class="font-semibold text-xl mb-4 text-emerald-700">4. Repositorio Digital</h3>
          <p class="text-gray-600">Creamos un sitio web abierto, sencillo y accesible para toda la comunidad juarense.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Saberes destacados -->
  <section id="saberes" class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-12">Saberes de Juárez</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="text-center">
          <div class="text-6xl mb-4">🌮</div>
          <h3 class="text-2xl font-semibold mb-2">Recetas Tradicionales</h3>
          <p class="text-gray-600">Burritos de machaca, discada, caldos fronterizos, sopa de fideo y más.</p>
        </div>
        <div class="text-center">
          <div class="text-6xl mb-4">🪔</div>
          <h3 class="text-2xl font-semibold mb-2">Artesanías y Oficios</h3>
          <p class="text-gray-600">Cerámica, talabartería, tejido, trabajo en madera y metal fronterizo.</p>
        </div>
        <div class="text-center">
          <div class="text-6xl mb-4">🎶</div>
          <h3 class="text-2xl font-semibold mb-2">Historias y Tradiciones</h3>
          <p class="text-gray-600">Leyendas de la frontera, bailes folclóricos, música norteña y memoria viva.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Galería -->
  <section id="galeria" class="py-20 bg-gray-900 text-white">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-12">Nuestra Comunidad</h2>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
        <img src="https://picsum.photos/600/400?random=1" class="rounded-xl" alt="Artesano">
        <img src="https://picsum.photos/600/400?random=2" class="rounded-xl" alt="Abuela cocinando">
        <img src="https://picsum.photos/600/400?random=3" class="rounded-xl" alt="Baile folclórico">
        <img src="https://picsum.photos/600/400?random=4" class="rounded-xl" alt="Cerámica">
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-gray-400 py-12">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <p class="text-2xl font-semibold text-white mb-2">Saberes Juárez</p>
      <p class="mb-6">Preservando nuestra identidad cultural • Ciudad Juárez, Chihuahua</p>
      <p class="text-sm">© 2026 - Proyecto educativo colaborativo con software libre</p>
    </div>
  </footer>

</body>
</html>
