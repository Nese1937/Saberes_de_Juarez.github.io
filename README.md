<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> Saberes de Juárez | Web de Saberes Comunitarios </title>
  <article class="proposito-blog">
    <!-- Imagen de la X al inicio con atributos de accesibilidad y tamaño -->
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQm6-ZzKQmLaXPMDTM6ajOm-pOuZeUJk0aehKUlsbqjfA&s" 
         alt="Monumento a la Mexicanidad conocido como la X en Ciudad Juárez" 
         style="max-width: 100%; height: auto; display: block; margin-bottom: 20px; border-radius: 8px;">

    <header>
        <h2>Propósito del blog</h2>
    </header>
    
    <main>
        <p>
            Este espacio nace para dar a conocer los <strong>saberes, las tradiciones, los platillos, conocimientos e historias</strong> de las personas de Ciudad Juárez. 
        </p>
        <p>
            Nuestro objetivo es ofrecer el <strong>reconocimiento que se merecen</strong>, además de visibilizar y concientizar sobre cuáles de estas expresiones culturales están en <em>peligro de desaparecer</em>.
        </p>
    </main>
</article>

<h1>Estoy aqui</h1>
<head>
    <!-- 1. Cargamos la librería Chart.js desde su servidor (CDN) -->
    <script src="https://jsdelivr.net"></script>
    <style>
        /* Estilo para que la gráfica no ocupe toda la pantalla */
        .contenedor-grafica {
            width: 80%;
            max-width: 600px;
            margin: 50px auto;
        }
    </style>
</head>
<body>
<
    <div class="contenedor-grafica">
        <!-- 2. El elemento HTML "canvas" donde se dibujará la gráfica -->
        <canvas id="miGrafica"></canvas>
    </div>
<
    <script>
        // 3. Obtenemos la referencia del canvas en JavaScript
        const ctx = document.getElementById('miGrafica').getContext('2d');
<
        // 4. Creamos y configuramos la gráfica
        const miGrafica = new Chart(ctx, {
            type: 'bar', // Tipo de gráfica: 'bar' (barras), 'line' (líneas), 'pie' (pastel)
            data: {
                labels: ['Enero', 'Febrero', 'Marzo', 'Abril', 'Mayo'], // Etiquetas del eje X
                datasets: [{
                    label: 'Ventas del Mes ($)',
                    data: [1200, 1900, 3000, 500, 2400], // Los datos numéricos
                    backgroundColor: [
                        'rgba(255, 99, 132, 0.5)',
                        'rgba(54, 162, 235, 0.5)',
                        'rgba(255, 206, 86, 0.5)',
                        'rgba(75, 192, 192, 0.5)',
                        'rgba(153, 102, 255, 0.5)'
                    ],
                    borderColor: [
                        'rgba(255, 99, 132, 1)',
                        'rgba(54, 162, 235, 1)',
                        'rgba(255, 206, 86, 1)',
                        'rgba(75, 192, 192, 1)',
                        'rgba(153, 102, 255, 1)'
                    ],
                    borderWidth: 1
                }]
            },
            options: {
                responsive: true,
                scales: {
                    y: {
                        beginAtZero: true // El eje Y siempre empieza en 0
                    }
                }
            }
        });
    </script>

</body>
</html>
