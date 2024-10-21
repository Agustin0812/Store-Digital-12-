<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Store Digital 12</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo Store Digital 12" class="logo">
        <h1>STORE DIGITAL 12</h1>
        <button id="desktop-view" onclick="toggleView()">Vista de Ordenador</button>
        <button id="cart-button" onclick="openCart()">🛒 Carrito (0)</button>
    </header>

    <main>
        <h2>Plataformas disponibles</h2>
        <div class="platforms">
            <div class="platform">
                <img src="netflix.png" alt="Netflix">
                <button onclick="addToCart('Netflix')">Añadir al Carrito</button>
            </div>
            <div class="platform">
                <img src="max.png" alt="Max">
                <button onclick="addToCart('Max')">Añadir al Carrito</button>
            </div>
            <div class="platform">
                <img src="disney.png" alt="Disney+">
                <button onclick="addToCart('Disney+')">Añadir al Carrito</button>
            </div>
            <div class="platform">
                <img src="prime.png" alt="Prime Video">
                <button onclick="addToCart('Prime Video')">Añadir al Carrito</button>
            </div>
            <div class="platform">
                <img src="paramount.png" alt="Paramount">
                <button onclick="addToCart('Paramount')">Añadir al Carrito</button>
            </div>
            <div class="platform">
                <img src="flujo.png" alt="Flujo TV">
                <button onclick="addToCart('Flujo TV')">Añadir al Carrito</button>
            </div>
        </div>
    </main>

    <div id="cart-modal" class="modal hidden">
        <div class="modal-content">
            <h3>Carrito de Compras</h3>
            <ul id="cart-items"></ul>
            <button onclick="checkout()">Finalizar Compra</button>
            <button onclick="closeCart()">Cerrar</button>
        </div>
    </div>

    <footer>
        <p>©️ 2024 STORE DIGITAL 12. Todos los derechos reservados.</p>
        <div class="contact">
            <a href="https://wa.me/595985671923" target="_blank">
                <img src="whatsapp.png" alt="WhatsApp"> +595 985671923
            </a>
            <a href="https://instagram.com/Store_digital12" target="_blank">
                <img src="instagram.png" alt="Instagram"> Store_digital12
            </a>
        </div>
    </footer>
</body>
</html>
