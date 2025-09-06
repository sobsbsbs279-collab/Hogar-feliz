
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hogar Feliz - Productos para Toda la Familia</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #5d4037;
            color: white;
            padding: 1.5rem 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        header h1 {
            font-size: 2.5rem;
            letter-spacing: 1px;
        }

        nav {
            background-color: #795548;
            padding: 1rem 0;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: 500;
            font-size: 1.1rem;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #ffe0b2;
        }

        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 20px;
        }

        .section-title {
            text-align: center;
            font-size: 2rem;
            margin: 2rem 0;
            color: #5d4037;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 3px;
            background-color: #8d6e63;
            margin: 10px auto;
        }

        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 30px;
            margin-top: 2rem;
        }

        .product-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0,0,0,0.15);
        }

        .product-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .product-info {
            padding: 1.5rem;
        }

        .product-info h3 {
            font-size: 1.3rem;
            margin-bottom: 0.5rem;
            color: #4e342e;
        }

        .product-info p {
            color: #6d4c41;
            margin-bottom: 1rem;
        }

        .btn {
            display: inline-block;
            background-color: #8d6e63;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #5d4037;
        }

        footer {
            background-color: #5d4037;
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 3rem;
        }

        footer p {
            margin: 5px 0;
        }

        @media (max-width: 768px) {
            .products-grid {
                grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>🏠 Hogar Feliz</h1>
        <p>Todo lo que necesitas para tu hogar y tu familia</p>
    </header>

    <nav>
        <a href="#mujeres">Para Mujeres</a>
        <a href="#hombres">Para Hombres</a>
        <a href="#juguetes">Juguetes Niños</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <div class="container">

        <!-- Sección Mujeres -->
        <section id="mujeres">
            <h2 class="section-title">Productos para Mujeres</h2>
            <div class="products-grid">
                <div class="product-card">
                    <img src="https://via.placeholder.com/300x200?text=Organizador+Elegante" alt="Organizador Elegante" class="product-img">
                    <div class="product-info">
                        <h3>Organizador de Joyas Elegante</h3>
                        <p>Diseño moderno y funcional para mantener tus accesorios en orden.</p>
                        <a href="#" class="btn">Ver más</a>
                    </div>
                </div>
                <div class="product-card">
                    <img src="https://via.placeholder.com/300x200?text=Bata+de+Seda" alt="Bata de Seda" class="product-img">
                    <div class="product-info">
                        <h3>Bata de Seda Suave</h3>
                        <p>Comodidad y estilo para tus momentos de relax en casa.</p>
                        <a href="#" class="btn">Ver más</a>
                    </div>
                </div>
                <div class="product-card">
                    <img src="https://via.placeholder.com/300x200?text=Set+de+Belleza" alt="Set de Belleza" class="product-img">
                    <div class="product-info">
                        <h3>Set de Belleza Premium</h3>
                        <p>Incluye espejo, brochas y organizador. Ideal para tu rutina diaria.</p>
                        <a href="#" class="btn">Ver más</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Sección Hombres -->
        <section id="hombres">
            <h2 class="section-title">Productos para Hombres</h2>
            <div class="products-grid">
                <div class="product-card">
                    <img src="https://via.placeholder.com/300x200?text=Porta+Herramientas" alt="Porta Herramientas" class="product-img">
                    <div class="product-info">
                        <h3>Maletín Porta Herramientas</h3>
                        <p>Resistente y con compartimentos organizados para tus herramientas.</p>
                        <a href="#" class="btn">Ver más</a>
                    </div>
                </div>
                <div class="product-card">
                    <img src="https://via.placeholder.com/300x200?text=Barbero+Home" alt="Kit Barbero Home" class="product-img">
                    <div class="product-info">
                        <h3>Kit de Afeitado Premium</h3>
                        <p>Todo lo necesario para un afeitado perfecto en casa.</p>
                        <a href="#" class="btn">Ver más</a>
                    </div>
                </div>
                <div class="product-card">
                    <img src="https://via.placeholder.com/300x200?text=Organizador+Escritorio" alt="Organizador Escritorio" class="product-img">
                    <div class="product-info">
                        <h3>Organizador de Escritorio Moderno</h3>
                        <p>Madera natural y diseño minimalista para tu espacio de trabajo.</p>
                        <a href="#" class="btn">Ver más</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Sección Juguetes -->
        <section id="juguetes">
            <h2 class="section-title">Juguetes para Niños</h2>
            <div class="products-grid">
                <div class="product-card">
                    <img src="https://via.placeholder.com/300x200?text=Robot+Educativo" alt="Robot Educativo" class="product-img">
                    <div class="product-info">
                        <h3>Robot Educativo Programable</h3>
                        <p>Fomenta el aprendizaje STEM mientras se divierten construyendo y programando.</p>
                        <a href="#" class="btn">Ver más</a>
                    </div>
                </div>
                <div class="product-card">
                    <img src="https://via.placeholder.com/300x200?text=Set+Cocinita" alt="Set Cocinita" class="product-img">
                    <div class="product-info">
                        <h3>Cocinita de Juguete con Accesorios</h3>
                        <p>Incluye utensilios, sonidos y luces. Ideal para horas de juego imaginativo.</p>
                        <a href="#" class="btn">Ver más</a>
                    </div>
                </div>
                <div class="product-card">
                    <img src="https://via.placeholder.com/300x200?text=Puzzle+Gigante" alt="Puzzle Gigante" class="product-img">
                    <div class="product-info">
                        <h3>Puzzle Gigante de Animales</h3>
                        <p>100 piezas grandes y coloridas para desarrollar habilidades motoras y cognitivas.</p>
                        <a href="#" class="btn">Ver más</a>
                    </div>
                </div>
            </div>
        </section>

    </div>

    <footer id="contacto">
        <p>📞 Contáctanos: contacto@hogarfeliz.com</p>
        <p>📍 Dirección: Av. Siempre Viva 123, Ciudad Feliz</p>
        <p>© 2025 Hogar Feliz. Todos los derechos reservados.</p>
    </footer>

</body>
</html>

