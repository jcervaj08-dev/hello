# hello
mi tienda

        <div id="contenedor-productos" class="productos-grid">
            <!-- Los productos se cargarán aquí con JavaScript -->
        </div>
    </main>

    <footer>
        <p>Contáctanos: <a href="https://wa.me/53512345678">WhatsApp</a></p>
    </footer>

    <script src="js/productos.js"></script>
    <script src="js/script.js"></script>
</body>
</html>html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plastic-Hogar Camagüey</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <h1>Plastic-Hogar</h1>
        <p>CAMAGÜEY · CUBA · ENVÍOS LOCALES</p>
    </header>
    <main>
        <h2>Todo para tu Hogar</h2>
        <p>Vasos, poqueles, recipientes y mucho más.</p>
        ```css
/* Estilos generales */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
}

header {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 20px;
}

.productos-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
    padding: 20px;
    max-width: 1200px;
    margin: 0 auto;
}

.producto {
    background: white;
    border-radius: 8px;
    padding: 15px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    transition: transform 0.3s;
}

.producto:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

.producto img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 4px;
}

.producto h3 {
    margin: 10px 0;
    
        
