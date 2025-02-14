<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZEMA - Trazabilidad Digital Textil</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50">
    <!-- Navbar -->
    <nav class="bg-white shadow-sm fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex justify-between items-center h-16">
                <div class="flex items-center">
                    <span class="text-2xl font-light tracking-wider">ZEMA</span>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#inicio" class="text-gray-700 hover:text-black">Inicio</a>
                    <a href="#soluciones" class="text-gray-700 hover:text-black">Soluciones</a>
                    <a href="#beneficios" class="text-gray-700 hover:text-black">Beneficios</a>
                    <a href="#contacto" class="text-gray-700 hover:text-black">Contacto</a>
                </div>
                <button class="bg-black text-white px-6 py-2 rounded-none hover:bg-gray-900">
                    Solicitar Demo
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="inicio" class="pt-24 pb-12 bg-black">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center justify-between">
                <div class="md:w-1/2 text-white">
                    <h1 class="text-4xl md:text-5xl font-light mb-6">
                        Revoluciona tu cadena de suministro textil
                    </h1>
                    <p class="text-xl mb-8 text-gray-300 font-light">
                        Conectamos toda tu cadena de suministro mediante etiquetado digital inteligente. Trazabilidad completa desde la fabricación hasta el consumidor final.
                    </p>
                    <div class="flex space-x-4">
                        <button class="bg-white text-black px-8 py-3 rounded-none font-light hover:bg-gray-100">
                            Comenzar
                        </button>
                        <button class="border border-white text-white px-8 py-3 rounded-none font-light hover:bg-white hover:text-black">
                            Ver Demo
                        </button>
                    </div>
                </div>
                <div class="md:w-1/2 mt-8 md:mt-0">
                    <img src="/api/placeholder/600/400" alt="ZEMA Platform" class=""/>
                </div>
            </div>
        </div>
    </section>

    <!-- Soluciones Section -->
    <section id="soluciones" class="py-16">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-3xl font-light text-center mb-12">Soluciones por Industria</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Manufactura -->
                <div class="bg-white p-6 border border-gray-200">
                    <div class="w-12 h-12 bg-gray-100 flex items-center justify-center mb-4">
                        <i class="fas fa-industry text-gray-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-light mb-4">Manufactura</h3>
                    <ul class="space-y-2 text-gray-600">
                        <li>• Control de producción</li>
                        <li>• Gestión de calidad</li>
                        <li>• Trazabilidad de materiales</li>
                        <li>• Etiquetado digital</li>
                    </ul>
                </div>
                <!-- Logística -->
                <div class="bg-white p-6 border border-gray-200">
                    <div class="w-12 h-12 bg-gray-100 flex items-center justify-center mb-4">
                        <i class="fas fa-truck text-gray-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-light mb-4">Logística</h3>
                    <ul class="space-y-2 text-gray-600">
                        <li>• Seguimiento en tiempo real</li>
                        <li>• Optimización de rutas</li>
                        <li>• Control de entregas</li>
                        <li>• Gestión de inventario</li>
                    </ul>
                </div>
                <!-- Retail -->
                <div class="bg-white p-6 border border-gray-200">
                    <div class="w-12 h-12 bg-gray-100 flex items-center justify-center mb-4">
                        <i class="fas fa-store text-gray-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-light mb-4">Retail</h3>
                    <ul class="space-y-2 text-gray-600">
                        <li>• Autenticación de productos</li>
                        <li>• Control de inventario</li>
                        <li>• Experiencia del cliente</li>
                        <li>• Análisis de ventas</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Beneficios Section -->
    <section id="beneficios" class="py-16 bg-gray-100">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-3xl font-light text-center mb-12">Beneficios</h2>
            <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
                <div class="text-center">
                    <div class="w-16 h-16 bg-gray-200 flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-shield-alt text-gray-700 text-2xl"></i>
                    </div>
                    <h3 class="font-light mb-2">Seguridad</h3>
                    <p class="text-gray-600">Protección contra falsificaciones y fraudes</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-gray-200 flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-chart-line text-gray-700 text-2xl"></i>
                    </div>
                    <h3 class="font-light mb-2">Eficiencia</h3>
                    <p class="text-gray-600">Optimización de procesos y recursos</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-gray-200 flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-search text-gray-700 text-2xl"></i>
                    </div>
                    <h3 class="font-light mb-2">Transparencia</h3>
                    <p class="text-gray-600">Trazabilidad completa end-to-end</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-gray-200 flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-leaf text-gray-700 text-2xl"></i>
                    </div>
                    <h3 class="font-light mb-2">Sostenibilidad</h3>
                    <p class="text-gray-600">Apoyo a prácticas sustentables</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-16 bg-black">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <h2 class="text-3xl font-light text-white mb-8">
                Comienza tu transformación digital hoy
            </h2>
            <p class="text-xl text-gray-300 mb-8 font-light">
                Únete a las empresas que ya están revolucionando su cadena de suministro
            </p>
            <button class="bg-white text-black px-8 py-3 rounded-none font-light hover:bg-gray-100">
                Solicitar Demo
            </button>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-black text-white py-12">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <span class="text-2xl font-light tracking-wider block mb-4">ZEMA</span>
                    <p class="text-gray-400">
                        Transformando la industria textil con tecnología de punta
                    </p>
                </div>
                <div>
                    <h4 class="font-light mb-4">Soluciones</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li>Manufactura</li>
                        <li>Logística</li>
                        <li>Retail</li>
                        <li>Consumidor Final</li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-light mb-4">Empresa</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li>Sobre Nosotros</li>
                        <li>Contacto</li>
                        <li>Blog</li>
                        <li>Careers</li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-light mb-4">Conecta</h4>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i class="fab fa-linkedin text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i class="fab fa-twitter text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i class="fab fa-facebook text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i class="fab fa-instagram text-xl"></i>
                        </a>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-400">
                <p>&copy; 2024 ZEMA. Todos los derechos reservados.</p>
            </div>
        </div>
    </footer>
</body>
</html>
