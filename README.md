<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Black Garlic Patagonia - Ajo Negro Gourmet</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@300;400;700&display=swap');
        
        :root {
            --color-negro-ajo: #1C1C1C;
            --color-dorado: #D4AF37;
            --color-tierra: #5D4037;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: #F5F5F5;
            scroll-behavior: smooth;
        }

        .fuente-titulo {
            font-family: 'Playfair Display', serif;
        }

        .hero-background {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
                        url('/api/placeholder/1920/1080') no-repeat center center;
            background-size: cover;
            background-attachment: fixed;
        }

        .card-hover {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card-hover:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }

        .linea-decorativa {
            position: relative;
            text-align: center;
        }

        .linea-decorativa::before,
        .linea-decorativa::after {
            content: '';
            position: absolute;
            top: 50%;
            width: 30%;
            height: 1px;
            background-color: var(--color-dorado);
        }

        .linea-decorativa::before {
            left: 0;
        }

        .linea-decorativa::after {
            right: 0;
        }
    </style>
</head>
<body class="text-gray-900">
    <!-- Navegación Elegante -->
    <nav class="fixed w-full z-50 bg-black bg-opacity-80 backdrop-blur-sm">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-3xl font-bold text-white fuente-titulo tracking-wider">
                Black Garlic Patagonia
            </h1>
            <div class="space-x-6 text-white">
                <a href="#inicio" class="hover:text-yellow-500 transition">Inicio</a>
                <a href="#nosotros" class="hover:text-yellow-500 transition">Nosotros</a>
                <a href="#productos" class="hover:text-yellow-500 transition">Productos</a>
                <a href="#contacto" class="bg-yellow-600 px-4 py-2 rounded-full hover:bg-yellow-700 transition">Contacto</a>
            </div>
        </div>
    </nav>

    <!-- Hero Premium -->
    <header id="inicio" class="hero-background text-white text-center pt-40 pb-32">
        <div class="container mx-auto px-6">
            <h2 class="text-6xl fuente-titulo mb-6 font-bold">
                Ajo Negro Artesanal
            </h2>
            <p class="text-xl max-w-2xl mx-auto mb-10 leading-relaxed">
                Un viaje gastronómico desde los fértiles suelos de Chiloé, donde cada bulbo cuenta una historia milenaria de transformación y sabor.
            </p>
            <a href="#productos" class="inline-block bg-yellow-600 text-white px-8 py-4 rounded-full text-lg font-bold hover:bg-yellow-700 transition">
                Descubre Nuestros Productos
            </a>
        </div>
    </header>

    <!-- Sección Nosotros -->
    <section id="nosotros" class="py-24 bg-white">
        <div class="container mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
            <div class="space-y-6">
                <h2 class="text-4xl fuente-titulo font-bold mb-4 text-gray-900">
                    Nuestra Historia
                </h2>
                <p class="text-gray-700 leading-relaxed">
                    En Black Garlic Patagonia, transformamos el ajo tradicional en un manjar gourmet, preservando técnicas ancestrales de Chiloé. Cada bulbo es un testimonio de nuestra pasión por la gastronomía y el respeto a nuestras raíces.
                </p>
                <div class="grid grid-cols-3 gap-4 text-center">
                    <div>
                        <h3 class="text-3xl font-bold text-yellow-600">+10</h3>
                        <p class="text-sm text-gray-600">Años de Tradición</p>
                    </div>
                    <div>
                        <h3 class="text-3xl font-bold text-yellow-600">100%</h3>
                        <p class="text-sm text-gray-600">Natural</p>
                    </div>
                    <div>
                        <h3 class="text-3xl font-bold text-yellow-600">5</h3>
                        <p class="text-sm text-gray-600">Premios Regionales</p>
                    </div>
                </div>
            </div>
            <div>
                <img src="/api/placeholder/600/500" alt="Proceso Artesanal" class="rounded-lg shadow-2xl transform -rotate-3">
            </div>
        </div>
    </section>

    <!-- Productos Gourmet -->
    <section id="productos" class="py-24 bg-gray-100">
        <div class="container mx-auto px-6 text-center mb-12">
            <h2 class="text-4xl fuente-titulo font-bold mb-4 linea-decorativa">
                Nuestra Línea Gourmet
            </h2>
            <p class="text-gray-700 max-w-2xl mx-auto">
                Cada producto es una experiencia sensorial única, elaborada con la más alta dedicación y respeto por los sabores tradicionales.
            </p>
        </div>
        
        <div class="grid md:grid-cols-3 gap-8 px-6">
            <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                <img src="/api/placeholder/400/400" alt="Ajo Negro Clásico" class="mx-auto mb-6 rounded-full">
                <h3 class="text-2xl font-bold mb-4">Ajo Negro Clásico</h3>
                <p class="text-gray-600 mb-6">Fermentación tradicional, sabor intenso y profundo.</p>
                <a href="#" class="inline-block bg-black text-white px-6 py-3 rounded-full hover:bg-gray-800 transition">
                    Comprar Ahora
                </a>
            </div>
            <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                <img src="/api/placeholder/400/400" alt="Ajo Negro Premium" class="mx-auto mb-6 rounded-full">
                <h3 class="text-2xl font-bold mb-4">Edición Premium</h3>
                <p class="text-gray-600 mb-6">Selección exclusiva, fermentación extendida.</p>
                <a href="#" class="inline-block bg-black text-white px-6 py-3 rounded-full hover:bg-gray-800 transition">
                    Comprar Ahora
                </a>
            </div>
            <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                <img src="/api/placeholder/400/400" alt="Pack Degustación" class="mx-auto mb-6 rounded-full">
                <h3 class="text-2xl font-bold mb-4">Pack Degustación</h3>
                <p class="text-gray-600 mb-6">Experimenta nuestra línea completa de sabores.</p>
                <a href="#" class="inline-block bg-black text-white px-6 py-3 rounded-full hover:bg-gray-800 transition">
                    Comprar Ahora
                </a>
            </div>
        </div>
    </section>

    <!-- Footer Elegante -->
    <footer class="bg-black text-white py-16">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-4xl fuente-titulo mb-6">Black Garlic Patagonia</h2>
            <p class="max-w-2xl mx-auto mb-8 text-gray-300">
                Transformando el ajo tradicional en una experiencia gastronómica única, con el corazón puesto en cada bulbo.
            </p>
            <div class="flex justify-center space-x-6 mb-8">
                <a href="#" class="text-white hover:text-yellow-500">Instagram</a>
                <a href="#" class="text-white hover:text-yellow-500">Facebook</a>
                <a href="#" class="text-white hover:text-yellow-500">Email</a>
            </div>
            <p class="text-sm text-gray-500">
                © 2024 Black Garlic Patagonia. Todos los derechos reservados.
            </p>
        </div>
    </footer>
</body>
</html>
