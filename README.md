# inventory-website
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inventario de Autos en Línea</title>
    <!-- Enlaza tu hoja de estilo CSS -->
    <link rel="stylesheet" href="estilos.css">
</head>
<body>
    <header>
        <h1>Inventario de Autos en Línea</h1>
    </header>
    <main>
        <section id="lista-autos">
            <h2>Autos Disponibles</h2>
            <ul>
                <li>
                    <h3>Auto 1</h3>
                    <p>Descripción del Auto 1</p>
                    <p>Precio: $XX,XXX</p>
                </li>
                <li>
                    <h3>Auto 2</h3>
                    <p>Descripción del Auto 2</p>
                    <p>Precio: $XX,XXX</p>
                </li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Inventario de Autos en Línea</p>
    </footer>
</body>
</html>
/* Establece la fuente para todo el cuerpo de la página */
body {
    font-family: "IBM Plex Sans", sans-serif;
}

/* Estiliza el encabezado de la página */
header {
    background-color: #0074E4; /* Azul principal */
    color: #FFFFFF; /* Texto blanco */
    padding: 20px;
    text-align: center;
}

header h1 {
    font-size: 32px;
}

/* Estiliza la lista de autos */
#lista-autos {
    margin: 20px;
}

ul {
    list-style: none;
    padding: 0;
}

li {
    background-color: #E6F0FF; /* Azul claro */
    border: 1px solid #0074E4; /* Borde del mismo color que el encabezado */
    padding: 10px;
    margin: 10px 0;
    border-radius: 5px;
}

li h3 {
    font-size: 24px;
    margin: 0;
}

li p {
    margin: 5px 0;
}

/* Estiliza el pie de página */
footer {
    background-color: #0074E4; /* Azul principal */
    color: #FFFFFF; /* Texto blanco */
    text-align: center;
    padding: 10px;
}
