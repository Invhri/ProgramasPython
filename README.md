<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo de Videojuegos</title>
    <link rel="stylesheet" href="styles.css"> <!-- Enlaza con tu archivo CSS -->
</head>
<body>

    <!-- Cabecera de la página -->
    <header>
        <div class="logo">
            <h1>Mi Catálogo de Videojuegos</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Acerca de</a></li>
                <li><a href="#">Contactos</a></li>
            </ul>
        </nav>
    </header>

    <!-- Filtro de búsqueda (opcional) -->
    <section class="search-bar">
        <input type="text" id="search" placeholder="Buscar un videojuego...">
    </section>

    <!-- Sección de Videojuegos -->
    <section class="catalog">
        <div class="game-card">
            <img src="juego1.jpg" alt="Juego 1">
            <h3>Juego 1</h3>
            <p>Descripción del videojuego 1.</p>
            <button>Ver detalles</button>
        </div>

        <div class="game-card">
            <img src="juego2.jpg" alt="Juego 2">
            <h3>Juego 2</h3>
            <p>Descripción del videojuego 2.</p>
            <button>Ver detalles</button>
        </div>

        <div class="game-card">
            <img src="juego3.jpg" alt="Juego 3">
            <h3>Juego 3</h3>
            <p>Descripción del videojuego 3.</p>
            <button>Ver detalles</button>
        </div>

        <!-- Agrega más tarjetas de videojuegos aquí -->
    </section>

    <!-- Pie de página -->
    <footer>
        <p>&copy; 2025 Mi Catálogo de Videojuegos</p>
    </footer>

    <script src="script.js"></script> <!-- Archivo JavaScript si es necesario -->
</body>
</html>

    padding: 10px;
    text-align: center;
    margin-top: 20px;
}
