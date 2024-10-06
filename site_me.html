<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sistema de Usuarios y Ventas</title>
<style>
    :root {
        --primary-color: #007bff;
        --secondary-color: #6c757d;
        --success-color: #28a745;
        --danger-color: #dc3545;
        --light-color: #f8f9fa;
        --dark-color: #343a40;
        --highlight-color: #90EE90;
    }
    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        margin: 0;
        padding: 20px;
        background-color: var(--light-color);
        color: var(--dark-color);
    }
    .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
        background-color: #fff;
        border-radius: 8px;
        box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h1, h2, h3 {
        color: var(--primary-color);
    }
    .form-group {
        margin-bottom: 1rem;
    }
    .form-group label {
        display: block;
        margin-bottom: 0.5rem;
    }
    input, select, button {
        width: 100%;
        padding: 0.5rem;
        border: 1px solid #ced4da;
        border-radius: 0.25rem;
    }
    button {
        background-color: var(--primary-color);
        color: white;
        border: none;
        cursor: pointer;
        transition: background-color 0.3s;
    }
    button:hover {
        background-color: #0056b3;
    }
    .btn-secondary {
        background-color: var(--secondary-color);
    }
    .btn-secondary:hover {
        background-color: #5a6268;
    }
    #mensaje, #notificacion {
        padding: 1rem;
        margin-bottom: 1rem;
        border-radius: 0.25rem;
        display: none;
    }
    .mensaje-error {
        background-color: var(--danger-color);
        color: white;
    }
    .mensaje-exito {
        background-color: var(--success-color);
        color: white;
    }
    .grid-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 1rem;
    }
    .column {
        background-color: var(--light-color);
        padding: 1rem;
        border-radius: 0.25rem;
    }
    .hidden {
        display: none;
    }
    .search-results {
        margin-top: 1rem;
        border: 1px solid #ced4da;
        border-radius: 0.25rem;
        max-height: 300px;
        overflow-y: auto;
    }
    .search-result-item {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0.5rem;
        border-bottom: 1px solid #ced4da;
    }
    .search-result-item:last-child {
        border-bottom: none;
    }
    .highlight {
        background-color: var(--highlight-color);
        font-weight: bold;
    }
    .venta-grid {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        gap: 1rem;
    }
    .venta-search {
        grid-column: 1 / -1;
    }
    .venta-results, .venta-datos, .venta-cart {
        border: 1px solid #ced4da;
        border-radius: 0.25rem;
        padding: 1rem;
        max-height: 400px;
        overflow-y: auto;
    }
    .modal {
        display: none;
        position: fixed;
        z-index: 1;
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
        overflow: auto;
        background-color: rgba(0,0,0,0.4);
    }
    .modal-content {
        background-color: #fefefe;
        margin: 15% auto;
        padding: 20px;
        border: 1px solid #888;
        width: 80%;
        max-width: 500px;
    }
    .close {
        color: #aaa;
        float: right;
        font-size: 28px;
        font-weight: bold;
    }
    .close:hover,
    .close:focus {
        color: black;
        text-decoration: none;
        cursor: pointer;
    }
    table {
        width: 100%;
        border-collapse: collapse;
    }
    th, td {
        padding: 8px;
        text-align: left;
        border-bottom: 1px solid #ddd;
    }
    th {
        background-color: var(--primary-color);
        color: white;
        cursor: pointer;
    }
    tr:hover {
        background-color: #f5f5f5;
    }
    .search-row {
        display: flex;
        gap: 1rem;
    }
    .search-row .form-group {
        flex: 1;
    }
</style>
</head>
<body>
<div class="container">
    <header>
        <h1>Sistema de Usuarios y Ventas</h1>
    </header>
    <main>
        <div id="mensaje"></div>
        <div id="notificacion"></div>

        <section id="loginSection">
            <h2>Iniciar Sesión</h2>
            <form id="loginForm">
                <div class="form-group">
                    <label for="username">Usuario:</label>
                    <input type="text" id="username" required>
                </div>
                <div class="form-group">
                    <label for="password">Contraseña:</label>
                    <input type="password" id="password" required>
                </div>
                <button type="submit">Iniciar Sesión</button>
            </form>
            <div class="form-group">
                <button onclick="mostrarSeccion('crearUsuarioSection')" class="btn-secondary">Crear Usuario</button>
                <button onclick="mostrarSeccion('borrarUsuarioSection')" class="btn-secondary">Borrar Usuario</button>
            </div>
        </section>

        <section id="crearUsuarioSection" class="hidden">
            <h2>Crear Usuario</h2>
            <form id="crearUsuarioForm">
                <div class="form-group">
                    <label for="nuevoUsuario">Nuevo Usuario:</label>
                    <input type="text" id="nuevoUsuario" required>
                </div>
                <div class="form-group">
                    <label for="nuevaContrasena">Nueva Contraseña:</label>
                    <input type="password" id="nuevaContrasena" required>
                </div>
                <div class="form-group">
                    <label for="contrasenaAdmin">Contraseña de Administrador:</label>
                    <input type="password" id="contrasenaAdmin" required>
                </div>
                <button type="submit">Crear Usuario</button>
            </form>
            <button onclick="mostrarSeccion('loginSection')" class="btn-secondary">Volver</button>
        </section>

        <section id="borrarUsuarioSection" class="hidden">
            <h2>Borrar Usuario</h2>
            <form id="borrarUsuarioForm">
                <div class="form-group">
                    <label for="usuarioABorrar">Usuario a Borrar:</label>
                    <input type="text" id="usuarioABorrar" required>
                </div>
                <div class="form-group">
                    <label for="contrasenaAdminBorrar">Contraseña de Administrador:</label>
                    <input type="password" id="contrasenaAdminBorrar" required>
                </div>
                <button type="submit">Borrar Usuario</button>
            </form>
            <button onclick="mostrarSeccion('loginSection')" class="btn-secondary">Volver</button>
        </section>

        <section id="ventaRegistro" class="hidden">
            <h2>Registro de Ventas</h2>
            <div class="grid-container">
                <div class="column">
                    <h3>Gestión de Productos</h3>
                    <button onclick="mostrarSeccion('anadirProductoSection')">Añadir Producto</button>
                    <button onclick="mostrarSeccion('borrarProductoSection')">Borrar Producto</button>
                    <button onclick="mostrarSeccion('mostrarProductosSection')">Mostrar Productos</button>
                </div>
                <div class="column">
                    <h3>Búsqueda de Productos</h3>
                    <div class="form-group">
                        <label for="buscarProducto">Búsqueda Exacta:</label>
                        <input type="text" id="buscarProducto" placeholder="Buscar producto...">
                    </div>
                    <div class="form-group">
                        <label for="buscarProductoRelacion">Búsqueda por Relación:</label>
                        <input type="text" id="buscarProductoRelacion" placeholder="Buscar producto por relación...">
                    </div>
                    <div class="search-row">
                        <div class="form-group">
                            <label for="buscarProductoSeparado">Búsqueda Separada:</label>
                            <input type="text" id="buscarProductoSeparado" placeholder="Buscar palabras separadas...">
                        </div>
                        <div class="form-group">
                            <label for="filtroProducto">Filtro:</label>
                            <input type="text" id="filtroProducto" placeholder="Filtrar resultados...">
                        </div>
                    </div>
                    <div class="form-group">
                        <label>
                            <input type="checkbox" id="resaltarResultados" checked> Resaltar resultados
                        </label>
                    </div>
                    <div id="resultadoBusqueda"></div>
                </div>
                <div class="column">
                    <h3>Zona de Venta</h3>
                    <button onclick="abrirTurnoVenta()" id="btnAbrirTurno">Abrir Turno De Venta</button>
                    <button onclick="cerrarTurnoVenta()" id="btnCerrarTurno" disabled>Cerrar Turno</button>
                    <button onclick="mostrarSeccion('crearVentaSection')" id="btnCrearVenta" disabled>Crear Venta</button>
                    <button onclick="mostrarSeccion('registroCambiosPrecioSection')">Registro de Cambios de Precio</button>
                    <button onclick="mostrarSeccion('registroVentasSection')">Registro de Ventas</button>
                    <button onclick="mostrarSeccion('registroTurnosSection')">Registro de Turnos</button>
                </div>
            </div>
            <div id="adminOptions" class="hidden">
                <h3>Opciones de Administrador</h3>
                <button onclick="mostrarSeccion('adminVentasSection')">Ver Ventas de Todos los Usuarios</button>
                <button onclick="mostrarSeccion('adminTurnosSection')">Ver Turnos de Todos los Usuarios</button>
            </div>
            <button onclick="cerrarSesion()" class="btn-secondary">Cerrar Sesión</button>
        </section>

        <section id="anadirProductoSection" class="hidden">
            <h2>Añadir Producto</h2>
            <form id="anadirProductoForm">
                <div class="form-group">
                    <label for="nombreProducto">Nombre del Producto:</label>
                    <input type="text" id="nombreProducto" required>
                </div>
                <div class="form-group">
                    <label for="tipoProducto">Tipo de Producto:</label>
                    <input type="text" id="tipoProducto" required>
                </div>
                <div class="form-group">
                    <label for="cantidadProducto">Cantidad:</label>
                    <input type="number" id="cantidadProducto" required min="1">
                </div>
                <div class="form-group">
                    <label for="precioProducto">Precio del Producto:</label>
                    <input type="number" id="precioProducto" required min="0" step="0.01">
                </div>
                <div class="form-group">
                    <label for="marcaProducto">Marca del Producto:</label>
                    <input type="text" id="marcaProducto" required>
                </div>
                <button type="submit">Añadir Producto</button>
            </form>
            <button onclick="mostrarSeccion('ventaRegistro')" class="btn-secondary">Volver</button>
        </section>

        <section id="borrarProductoSection" class="hidden">
            <h2>Borrar Producto</h2>
            <form id="borrarProductoForm">
                <div class="form-group">
                    <label for="nombreProductoBorrar">Nombre del Producto a Borrar:</label>
                    <input type="text" id="nombreProductoBorrar" required>
                </div>
                <button type="submit">Borrar Producto</button>
            </form>
            <button onclick="mostrarSeccion('ventaRegistro')" class="btn-secondary">Volver</button>
        </section>

        <section id="mostrarProductosSection" class="hidden">
            <h2>Mostrar Productos</h2>
            <table id="tablaProductos">
                <thead>
                    <tr>
                        <th onclick="ordenarTabla('nombre')">Nombre de Producto</th>
                        <th onclick="ordenarTabla('tipo')">Tipo de Producto</th>
                        <th onclick="ordenarTabla('cantidad')">Cantidad</th>
                        <th onclick="ordenarTabla('precio')">Precio del Producto</th>
                        <th onclick="ordenarTabla('marca')">Marca del Producto</th>
                    </tr>
                </thead>
                <tbody id="cuerpoTablaProductos">
                    <!-- Aquí se insertarán las filas de productos dinámicamente -->
                </tbody>
            </table>
            <button onclick="mostrarSeccion('ventaRegistro')" class="btn-secondary">Volver</button>
        </section>

        <section id="crearVentaSection" class="hidden">
            <h2>Crear Venta</h2>
            <div class="venta-grid">
                <div class="venta-search">
                    <div class="form-group">
                        <label for="buscarProductoVenta">Búsqueda Exacta:</label>
                        <input type="text" id="buscarProductoVenta" placeholder="Buscar producto para venta...">
                    </div>
                    <div class="form-group">
                        <label for="buscarProductoVentaRelacion">Búsqueda por Relación:</label>
                        <input type="text" id="buscarProductoVentaRelacion" placeholder="Buscar producto por relación...">
                    </div>
                    <div class="form-group">
                        <label>
                            <input type="checkbox" id="resaltarResultadosVenta" checked> Resaltar resultados
                        </label>
                    </div>
                </div>
                <div class="venta-results">
                    <h3>Resultados de búsqueda</h3>
                    <div id="resultadosBusquedaVenta"></div>
                </div>
                <div class="venta-datos">
                    <h3>Datos Venta</h3>
                    <div id="datosVenta">
                        <p>Total de venta: $<span id="totalVenta">0.00</span></p>
                        <h4>Lista de productos:</h4>
                        <ul id="listaProductosVenta"></ul>
                        <div class="form-group">
                            <label for="medioPago">Medio de Pago:</label>
                            <select id="medioPago">
                                <option value="yape">Yape</option>
                                <option value="efectivo">Efectivo</option>
                                <option value="tarjeta">Tarjeta</option>
                                <option value="transferencia">Transferencia</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label for="formaPago">Forma de Pago:</label>
                            <select id="formaPago">
                                <option value="contado">Contado</option>
                                <option value="credito">Crédito</option>
                            </select>
                        </div>
                    </div>
                </div>
                <div class="venta-cart">
                    <h3>Carrito de venta</h3>
                    <div id="carritoVenta"></div>
                    <button onclick="emitirBoleta()" class="btn-secondary">Emitir Boleta</button>
                </div>
            </div>
            <button onclick="mostrarSeccion('ventaRegistro')" class="btn-secondary">Volver a Registro de Ventas</button>
        </section>

        <section id="registroCambiosPrecioSection" class="hidden">
            <h2>Registro de Cambios de Precio</h2>
            <div id="registroCambiosPrecio"></div>
            <button onclick="mostrarSeccion('ventaRegistro')" class="btn-secondary">Volver a Registro de Ventas</button>
        </section>

        <section id="registroVentasSection" class="hidden">
            <h2>Registro de Ventas</h2>
            <div id="registroVentas"></div>
            <button onclick="mostrarSeccion('ventaRegistro')" class="btn-secondary">Volver a Registro de Ventas</button>
        </section>

        <section id="registroTurnosSection" class="hidden">
            <h2>Registro de Turnos</h2>
            <div id="registroTurnos"></div>
            <button onclick="mostrarSeccion('ventaRegistro')" class="btn-secondary">Volver a Registro de Ventas</button>
        </section>

        <section id="adminVentasSection" class="hidden">
            <h2>Ventas de Todos los Usuarios</h2>
            <div id="adminRegistroVentas"></div>
            <button onclick="mostrarSeccion('ventaRegistro')" class="btn-secondary">Volver a Registro de Ventas</button>
        </section>

        <section id="adminTurnosSection" class="hidden">
            <h2>Turnos de Todos los Usuarios</h2>
            <div id="adminRegistroTurnos"></div>
            <button onclick="mostrarSeccion('ventaRegistro')" class="btn-secondary">Volver a Registro de Ventas</button>
        </section>
    </main>
</div>

<div id="modalEditarProducto" class="modal">
    <div class="modal-content">
        <span class="close">&times;</span>
        <h2>Editar Producto</h2>
        <form id="editarProductoForm">
            <div class="form-group">
                <label for="editarCantidad">Cantidad:</label>
                <input type="number" id="editarCantidad" required min="1">
            </div>
            <div class="form-group">
                <label for="editarPrecio">Precio:</label>
                <input type="number" id="editarPrecio" required min="0" step="0.01">
            </div>
            <button type="submit">Guardar Cambios</button>
        </form>
    </div>
</div>

<div id="modalConfirmarTurno" class="modal">
    <div class="modal-content">
        <span class="close">&times;</span>
        <h2>Confirmar Apertura de Turno</h2>
        <p id="mensajeConfirmarTurno"></p>
        <button onclick="confirmarAbrirTurno()">Confirmar</button>
        <button onclick="cerrarModal('modalConfirmarTurno')">Cancelar</button>
    </div>
</div>

<script>
    // Inicialización de datos
    if (!localStorage.getItem('usuarios')) {
        localStorage.setItem('usuarios', JSON.stringify({ 'jeremy': 'faraon99' }));
    }
    if (!localStorage.getItem('productos')) {
        localStorage.setItem('productos', JSON.stringify([
            { nombre: "cafarena de hilo", tipo: "Ropa", cantidad: 10, precio: 15.99, marca: "Cafarena" },
            { nombre: "cafarena rib grueso", tipo: "Ropa", cantidad: 8, precio: 18.99, marca: "Cafarena" },
            { nombre: "polera manga larga", tipo: "Ropa", cantidad: 15, precio: 22.99, marca: "Generic" }
        ]));
    }
    if (!localStorage.getItem('cambiosPrecio')) {
        localStorage.setItem('cambiosPrecio', JSON.stringify([]));
    }
    if (!localStorage.getItem('registroVentas')) {
        localStorage.setItem('registroVentas', JSON.stringify({}));
    }
    if (!localStorage.getItem('registroTurnos')) {
        localStorage.setItem('registroTurnos', JSON.stringify([]));
    }

    let usuarioActual = '';
    let carrito = [];
    let turnoActual = null;
    let ordenActual = { campo: null, ascendente: true };

    function mostrarMensaje(mensaje, tipo = 'error') {
        const mensajeElement = document.getElementById('mensaje');
        mensajeElement.textContent = mensaje;
        mensajeElement.className = tipo === 'error' ? 'mensaje-error' : 'mensaje-exito';
        mensajeElement.style.display = 'block';
        setTimeout(() => mensajeElement.style.display = 'none', 3000);
    }

    function mostrarNotificacion(mensaje) {
        const notificacionElement = document.getElementById('notificacion');
        notificacionElement.textContent = mensaje;
        notificacionElement.className = 'mensaje-exito';
        notificacionElement.style.display = 'block';
        setTimeout(() => notificacionElement.style.display = 'none', 3000);
    }

    function mostrarSeccion(id) {
        document.querySelectorAll('section').forEach(section => section.classList.add('hidden'));
        document.getElementById(id).classList.remove('hidden');
        if (id === 'registroCambiosPrecioSection') {
            mostrarRegistroCambiosPrecio();
        } else if (id === 'registroVentasSection') {
            mostrarRegistroVentas();
        } else if (id === 'registroTurnosSection') {
            mostrarRegistroTurnos();
        } else if (id === 'mostrarProductosSection') {
            mostrarProductos();
        } else if (id === 'adminVentasSection') {
            mostrarAdminVentas();
        } else if (id === 'adminTurnosSection') {
            mostrarAdminTurnos();
        }
    }

    function cerrarSesion() {
        usuarioActual = '';
        turnoActual = null;
        actualizarBotonesTurno();
        mostrarSeccion('loginSection');
        document.getElementById('username').value = '';
        document.getElementById('password').value = '';
        document.getElementById('adminOptions').classList.add('hidden');
    }

    document.getElementById('loginForm').addEventListener('submit', function(e) {
        e.preventDefault();
        const username = document.getElementById('username').value;
        const password = document.getElementById('password').value;
        const usuarios = JSON.parse(localStorage.getItem('usuarios'));
        if (usuarios[username] === password) {
            usuarioActual = username;
            mostrarMensaje('Inicio de sesión exitoso', 'exito');
            mostrarSeccion('ventaRegistro');
            actualizarBotonesTurno();
            if (username === 'jeremy') {
                document.getElementById('adminOptions').classList.remove('hidden');
            }
        } else {
            mostrarMensaje('Usuario o contraseña incorrectos');
        }
    });

    document.getElementById('crearUsuarioForm').addEventListener('submit', function(e) {
        e.preventDefault();
        const nuevoUsuario = document.getElementById('nuevoUsuario').value;
        const nuevaContrasena = document.getElementById('nuevaContrasena').value;
        const contrasenaAdmin = document.getElementById('contrasenaAdmin').value;
        if (contrasenaAdmin === 'cheremy123') {
            const usuarios = JSON.parse(localStorage.getItem('usuarios'));
            if (usuarios[nuevoUsuario]) {
                mostrarMensaje('El usuario ya existe');
            } else {
                usuarios[nuevoUsuario] = nuevaContrasena;
                localStorage.setItem('usuarios', JSON.stringify(usuarios));
                mostrarMensaje('Usuario creado exitosamente', 'exito');
                mostrarSeccion('loginSection');
            }
        } else {
            mostrarMensaje('Contraseña de administrador incorrecta');
        }
    });

    document.getElementById('borrarUsuarioForm').addEventListener('submit', function(e) {
        e.preventDefault();
        const usuarioABorrar = document.getElementById('usuarioABorrar').value;
        const contrasenaAdminBorrar = document.getElementById('contrasenaAdminBorrar').value;
        if (contrasenaAdminBorrar === 'cheremy123') {
            const usuarios = JSON.parse(localStorage.getItem('usuarios'));
            if (usuarioABorrar === 'jeremy') {
                mostrarMensaje('No se puede borrar el usuario administrador');
            } else if (usuarios[usuarioABorrar]) {
                delete usuarios[usuarioABorrar];
                localStorage.setItem('usuarios', JSON.stringify(usuarios));
                mostrarMensaje('Usuario borrado exitosamente', 'exito');
                mostrarSeccion('loginSection');
            } else {
                mostrarMensaje('El usuario no existe');
            }
        } else {
            mostrarMensaje('Contraseña de administrador incorrecta');
        }
    });

    document.getElementById('anadirProductoForm').addEventListener('submit', function(e) {
        e.preventDefault();
        const nuevoProducto = {
            nombre: document.getElementById('nombreProducto').value,
            tipo: document.getElementById('tipoProducto').value,
            cantidad: parseInt(document.getElementById('cantidadProducto').value),
            precio: parseFloat(document.getElementById('precioProducto').value),
            marca: document.getElementById('marcaProducto').value
        };
        const productos = JSON.parse(localStorage.getItem('productos'));
        productos.push(nuevoProducto);
        localStorage.setItem('productos', JSON.stringify(productos));
        mostrarMensaje('Producto añadido exitosamente', 'exito');
        this.reset();
    });

    document.getElementById('borrarProductoForm').addEventListener('submit', function(e) {
        e.preventDefault();
        const nombreProducto = document.getElementById('nombreProductoBorrar').value;
        let productos = JSON.parse(localStorage.getItem('productos'));
        const indiceProducto = productos.findIndex(p => p.nombre.toLowerCase() === nombreProducto.toLowerCase());
        if (indiceProducto !== -1) {
            productos.splice(indiceProducto, 1);
            localStorage.setItem('productos', JSON.stringify(productos));
            mostrarMensaje('Producto borrado exitosamente', 'exito');
        }
        else {
            mostrarMensaje('Producto no encontrado');
        }
        this.reset();
    });

    function buscarProductos() {
        const busqueda = document.getElementById('buscarProducto').value.toLowerCase();
        const productos = JSON.parse(localStorage.getItem('productos'));
        const resultados = productos.filter(p => 
            p.nombre.toLowerCase().includes(busqueda) || 
            p.tipo.toLowerCase().includes(busqueda) || 
            p.marca.toLowerCase().includes(busqueda)
        );
        mostrarResultadosBusqueda(resultados, false);
    }

    function buscarProductosRelacion() {
        const busqueda = document.getElementById('buscarProductoRelacion').value.toLowerCase();
        const productos = JSON.parse(localStorage.getItem('productos'));
        const resultados = productos.filter(p => 
            p.nombre.toLowerCase().includes(busqueda) || 
            p.tipo.toLowerCase().includes(busqueda) || 
            p.marca.toLowerCase().includes(busqueda)
        );
        mostrarResultadosBusqueda(resultados, true);
    }

    function buscarProductosSeparados() {
        const busqueda = document.getElementById('buscarProductoSeparado').value.toLowerCase();
        const palabras = busqueda.split(' ').filter(palabra => palabra.length > 0);
        const productos = JSON.parse(localStorage.getItem('productos'));
        const resultados = productos.filter(p => 
            palabras.every(palabra => 
                p.nombre.toLowerCase().includes(palabra) || 
                p.tipo.toLowerCase().includes(palabra) || 
                p.marca.toLowerCase().includes(palabra)
            )
        );
        mostrarResultadosBusqueda(resultados, false);
    }

    function aplicarFiltro() {
        const filtro = document.getElementById('filtroProducto').value.toLowerCase();
        const resultadosDiv = document.getElementById('resultadoBusqueda');
        const items = resultadosDiv.getElementsByTagName('li');
        
        for (let i = 0; i < items.length; i++) {
            const textoItem = items[i].textContent.toLowerCase();
            if (textoItem.includes(filtro)) {
                items[i].style.display = "";
            } else {
                items[i].style.display = "none";
            }
        }
    }

    function mostrarResultadosBusqueda(resultados, esRelacion) {
        const resultadosDiv = document.getElementById('resultadoBusqueda');
        if (resultados.length === 0) {
            resultadosDiv.innerHTML = '<p>No se encontraron productos.</p>';
        } else {
            let html = '<ul>';
            resultados.forEach(producto => {
                let nombreProducto = producto.nombre;
                if (esRelacion && document.getElementById('resaltarResultados').checked) {
                    const busqueda = document.getElementById('buscarProductoRelacion').value.toLowerCase();
                    nombreProducto = resaltarCoincidencias(nombreProducto, busqueda);
                }
                html += `<li>${nombreProducto} - ${producto.tipo} - ${producto.marca} - Cantidad: ${producto.cantidad} - Precio: $${producto.precio.toFixed(2)}</li>`;
            });
            html += '</ul>';
            resultadosDiv.innerHTML = html;
        }
    }

    function resaltarCoincidencias(texto, busqueda) {
        const regex = new RegExp(`(${busqueda})`, 'gi');
        return texto.replace(regex, '<span class="highlight">$1</span>');
    }

    document.getElementById('buscarProducto').addEventListener('input', buscarProductos);
    document.getElementById('buscarProductoRelacion').addEventListener('input', buscarProductosRelacion);
    document.getElementById('buscarProductoSeparado').addEventListener('input', buscarProductosSeparados);
    document.getElementById('filtroProducto').addEventListener('input', aplicarFiltro);
    document.getElementById('resaltarResultados').addEventListener('change', () => {
        if (document.getElementById('buscarProductoRelacion').value) {
            buscarProductosRelacion();
        }
    });

    function buscarProductosVenta() {
        const busqueda = document.getElementById('buscarProductoVenta').value.toLowerCase();
        const productos = JSON.parse(localStorage.getItem('productos'));
        const resultados = productos.filter(p => 
            p.nombre.toLowerCase().includes(busqueda) || 
            p.tipo.toLowerCase().includes(busqueda) || 
            p.marca.toLowerCase().includes(busqueda)
        );
        mostrarResultadosBusquedaVenta(resultados, false);
    }

    function buscarProductosVentaRelacion() {
        const busqueda = document.getElementById('buscarProductoVentaRelacion').value.toLowerCase();
        const productos = JSON.parse(localStorage.getItem('productos'));
        const resultados = productos.filter(p => 
            p.nombre.toLowerCase().includes(busqueda) || 
            p.tipo.toLowerCase().includes(busqueda) || 
            p.marca.toLowerCase().includes(busqueda)
        );
        mostrarResultadosBusquedaVenta(resultados, true);
    }

    function mostrarResultadosBusquedaVenta(resultados, esRelacion) {
        const resultadosDiv = document.getElementById('resultadosBusquedaVenta');
        if (resultados.length === 0) {
            resultadosDiv.innerHTML = '<p>No se encontraron productos.</p>';
        } else {
            let html = '<div class="search-results">';
            resultados.forEach(producto => {
                let nombreProducto = producto.nombre;
                if (esRelacion && document.getElementById('resaltarResultadosVenta').checked) {
                    const busqueda = document.getElementById('buscarProductoVentaRelacion').value.toLowerCase();
                    nombreProducto = resaltarCoincidencias(nombreProducto, busqueda);
                }
                html += `
                    <div class="search-result-item">
                        <span>${nombreProducto} - ${producto.tipo} - ${producto.marca} - Precio: $${producto.precio.toFixed(2)}</span>
                        <button class="add-button" onclick="agregarAlCarrito(${JSON.stringify(producto).replace(/"/g, '&quot;')})">+</button>
                    </div>
                `;
            });
            html += '</div>';
            resultadosDiv.innerHTML = html;
        }
    }

    document.getElementById('buscarProductoVenta').addEventListener('input', buscarProductosVenta);
    document.getElementById('buscarProductoVentaRelacion').addEventListener('input', buscarProductosVentaRelacion);
    document.getElementById('resaltarResultadosVenta').addEventListener('change', () => {
        if (document.getElementById('buscarProductoVentaRelacion').value) {
            buscarProductosVentaRelacion();
        }
    });

    function agregarAlCarrito(producto) {
        carrito.push({...producto, cantidadVenta: 1});
        actualizarCarritoVenta();
        actualizarDatosVenta();
    }

    function actualizarCarritoVenta() {
        const carritoDiv = document.getElementById('carritoVenta');
        if (carrito.length === 0) {
            carritoDiv.innerHTML = '<p>El carrito está vacío.</p>';
        } else {
            let html = '<ul>';
            carrito.forEach((producto, index) => {
                html += `
                    <li>
                        ${producto.nombre} - Cantidad: ${producto.cantidadVenta} - Precio: $${producto.precio.toFixed(2)}
                        <button onclick="editarProductoCarrito(${index})">Editar</button>
                        <button onclick="eliminarDelCarrito(${index})">Eliminar</button>
                    </li>
                `;
            });
            html += '</ul>';
            carritoDiv.innerHTML = html;
        }
    }

    function eliminarDelCarrito(index) {
        carrito.splice(index, 1);
        actualizarCarritoVenta();
        actualizarDatosVenta();
    }

    function calcularTotal() {
        return carrito.reduce((total, producto) => total + (producto.precio * producto.cantidadVenta), 0);
    }

    function actualizarDatosVenta() {
        const totalVentaElement = document.getElementById('totalVenta');
        const listaProductosVentaElement = document.getElementById('listaProductosVenta');
        
        totalVentaElement.textContent = calcularTotal().toFixed(2);
        
        let listaHtml = '';
        carrito.forEach(producto => {
            listaHtml += `<li>${producto.nombre} - Cantidad: ${producto.cantidadVenta} - Precio: $${(producto.precio * producto.cantidadVenta).toFixed(2)}</li>`;
        });
        listaProductosVentaElement.innerHTML = listaHtml;
    }

    function editarProductoCarrito(index) {
        const producto = carrito[index];
        document.getElementById('editarCantidad').value = producto.cantidadVenta;
        document.getElementById('editarPrecio').value = producto.precio;
        
        const modal = document.getElementById('modalEditarProducto');
        modal.style.display = 'block';

        const span = document.getElementsByClassName('close')[0];
        span.onclick = function() {
            modal.style.display = 'none';
        }

        window.onclick = function(event) {
            if (event.target == modal) {
                modal.style.display = 'none';
            }
        }

        document.getElementById('editarProductoForm').onsubmit = function(e) {
            e.preventDefault();
            const nuevaCantidad = parseInt(document.getElementById('editarCantidad').value);
            const nuevoPrecio = parseFloat(document.getElementById('editarPrecio').value);

            if (nuevoPrecio !== producto.precio) {
                registrarCambioPrecio(producto.nombre, producto.precio, nuevoPrecio);
            }

            carrito[index] = {...producto, cantidadVenta: nuevaCantidad, precio: nuevoPrecio};
            actualizarCarritoVenta();
            actualizarDatosVenta();
            modal.style.display = 'none';
        }
    }

    function registrarCambioPrecio(nombreProducto, precioAnterior, precioNuevo) {
        const cambiosPrecio = JSON.parse(localStorage.getItem('cambiosPrecio'));
        cambiosPrecio.push({
            nombreProducto,
            precioAnterior,
            precioNuevo,
            fecha: new Date().toISOString(),
            usuario: usuarioActual
        });
        localStorage.setItem('cambiosPrecio', JSON.stringify(cambiosPrecio));
    }

    function mostrarRegistroCambiosPrecio() {
        const cambiosPrecio = JSON.parse(localStorage.getItem('cambiosPrecio'));
        const registroDiv = document.getElementById('registroCambiosPrecio');
        if (usuarioActual === 'jeremy' || cambiosPrecio.some(cambio => cambio.usuario === usuarioActual)) {
            let html = '<ul>';
            cambiosPrecio.forEach(cambio => {
                html += `
                    <li>
                        Producto: ${cambio.nombreProducto}<br>
                        Precio anterior: $${cambio.precioAnterior.toFixed(2)}<br>
                        Precio nuevo: $${cambio.precioNuevo.toFixed(2)}<br>
                        Fecha: ${new Date(cambio.fecha).toLocaleString()}<br>
                        Usuario: ${cambio.usuario}
                    </li>
                `;
            });
            html += '</ul>';
            registroDiv.innerHTML = html;
        } else {
            registroDiv.innerHTML = '<p>No tienes permiso para ver este registro.</p>';
        }
    }

    function emitirBoleta() {
        if (carrito.length === 0) {
            mostrarMensaje('El carrito está vacío');
            return;
        }

        const registroVentas = JSON.parse(localStorage.getItem('registroVentas'));
        if (!registroVentas[usuarioActual]) {
            registroVentas[usuarioActual] = [];
        }
        const nuevaVenta = {
            numeroBoleta: registroVentas[usuarioActual].length + 1,
            fecha: new Date().toISOString(),
            productos: carrito,
            total: calcularTotal(),
            medioPago: document.getElementById('medioPago').value,
            formaPago: document.getElementById('formaPago').value
        };
        registroVentas[usuarioActual].push(nuevaVenta);
        localStorage.setItem('registroVentas', JSON.stringify(registroVentas));

        mostrarMensaje('Boleta emitida exitosamente', 'exito');
        carrito = [];
        actualizarCarritoVenta();
        actualizarDatosVenta();
    }

    function mostrarRegistroVentas() {
        const registroVentas = JSON.parse(localStorage.getItem('registroVentas'));
        const registroDiv = document.getElementById('registroVentas');
        if (registroVentas[usuarioActual]) {
            let html = '<ul>';
            registroVentas[usuarioActual].forEach(venta => {
                html += `
                    <li>
                        Número de Boleta: ${venta.numeroBoleta}<br>
                        Fecha: ${new Date(venta.fecha).toLocaleString()}<br>
                        Total: $${venta.total.toFixed(2)}<br>
                        Medio de Pago: ${venta.medioPago}<br>
                        Forma de Pago: ${venta.formaPago}
                    </li>
                `;
            });
            html += '</ul>';
            registroDiv.innerHTML = html;
        } else {
            registroDiv.innerHTML = '<p>No hay ventas registradas.</p>';
        }
    }

    function abrirTurnoVenta() {
        const registroTurnos = JSON.parse(localStorage.getItem('registroTurnos'));
        const turnoAbierto = registroTurnos.find(turno => !turno.fechaCierre);
        
        if (turnoAbierto) {
            document.getElementById('mensajeConfirmarTurno').textContent = 'Ya hay un turno abierto. ¿Deseas cerrarlo y abrir uno nuevo?';
        } else {
            document.getElementById('mensajeConfirmarTurno').textContent = '¿Deseas abrir un nuevo turno de venta?';
        }
        
        document.getElementById('modalConfirmarTurno').style.display = 'block';
    }

    function confirmarAbrirTurno() {
        const registroTurnos = JSON.parse(localStorage.getItem('registroTurnos'));
        const turnoAbierto = registroTurnos.find(turno => !turno.fechaCierre);
        
        if (turnoAbierto) {
            turnoAbierto.fechaCierre = new Date().toISOString();
        }
        
        const nuevoTurno = {
            fechaApertura: new Date().toISOString(),
            usuario: usuarioActual
        };
        registroTurnos.push(nuevoTurno);
        localStorage.setItem('registroTurnos', JSON.stringify(registroTurnos));
        
        turnoActual = nuevoTurno;
        actualizarBotonesTurno();
        mostrarNotificacion('Se abrió turno correctamente');
        cerrarModal('modalConfirmarTurno');
    }

    function cerrarTurnoVenta() {
        if (turnoActual) {
            const registroTurnos = JSON.parse(localStorage.getItem('registroTurnos'));
            const turnoIndex = registroTurnos.findIndex(turno => turno.fechaApertura === turnoActual.fechaApertura);
            if (turnoIndex !== -1) {
                registroTurnos[turnoIndex].fechaCierre = new Date().toISOString();
                localStorage.setItem('registroTurnos', JSON.stringify(registroTurnos));
                turnoActual = null;
                actualizarBotonesTurno();
                mostrarNotificacion('Turno cerrado correctamente');
            }
        } else {
            mostrarMensaje('No hay un turno abierto para cerrar');
        }
    }

    function actualizarBotonesTurno() {
        const btnAbrirTurno = document.getElementById('btnAbrirTurno');
        const btnCerrarTurno = document.getElementById('btnCerrarTurno');
        const btnCrearVenta = document.getElementById('btnCrearVenta');

        if (turnoActual) {
            btnAbrirTurno.disabled = true;
            btnCerrarTurno.disabled = false;
            btnCrearVenta.disabled = false;
        } else {
            btnAbrirTurno.disabled = false;
            btnCerrarTurno.disabled = true;
            btnCrearVenta.disabled = true;
        }
    }

    function mostrarRegistroTurnos() {
        const registroTurnos = JSON.parse(localStorage.getItem('registroTurnos'));
        const registroDiv = document.getElementById('registroTurnos');
        
        if (usuarioActual === 'jeremy') {
            let html = '<ul>';
            registroTurnos.forEach(turno => {
                html += `
                    <li>
                        Usuario: ${turno.usuario}<br>
                        Fecha de apertura: ${new Date(turno.fechaApertura).toLocaleString()}<br>
                        Fecha de cierre: ${turno.fechaCierre ? new Date(turno.fechaCierre).toLocaleString() : 'Turno abierto'}
                    </li>
                `;
            });
            html += '</ul>';
            registroDiv.innerHTML = html;
        } else {
            registroDiv.innerHTML = '<p>No tienes permiso para ver este registro.</p>';
        }
    }

    function cerrarModal(modalId) {
        document.getElementById(modalId).style.display = 'none';
    }

    // Event listeners para cerrar modales
    window.onclick = function(event) {
        if (event.target.className === 'modal') {
            event.target.style.display = 'none';
        }
    }

    document.querySelectorAll('.close').forEach(closeBtn => {
        closeBtn.onclick = function() {
            this.closest('.modal').style.display = 'none';
        }
    });

    function mostrarProductos() {
        const productos = JSON.parse(localStorage.getItem('productos'));
        const tbody = document.getElementById('cuerpoTablaProductos');
        tbody.innerHTML = '';
        productos.forEach(producto => {
            const tr = document.createElement('tr');
            tr.innerHTML = `
                <td>${producto.nombre}</td>
                <td>${producto.tipo}</td>
                <td>${producto.cantidad}</td>
                <td>$${producto.precio.toFixed(2)}</td>
                <td>${producto.marca}</td>
            `;
            tbody.appendChild(tr);
        });
    }

    function ordenarTabla(campo) {
        if (ordenActual.campo === campo) {
            ordenActual.ascendente = !ordenActual.ascendente;
        } else {
            ordenActual.campo = campo;
            ordenActual.ascendente = true;
        }

        const productos = JSON.parse(localStorage.getItem('productos'));
        productos.sort((a, b) => {
            if (campo === 'cantidad' || campo === 'precio') {
                return ordenActual.ascendente ? a[campo] - b[campo] : b[campo] - a[campo];
            } else {
                return ordenActual.ascendente ? 
                    a[campo].localeCompare(b[campo]) : 
                    b[campo].localeCompare(a[campo]);
            }
        });
        localStorage.setItem('productos', JSON.stringify(productos));
        mostrarProductos();
    }

    function mostrarAdminVentas() {
        const registroVentas = JSON.parse(localStorage.getItem('registroVentas'));
        const registroDiv = document.getElementById('adminRegistroVentas');
        let html = '';
        for (const usuario in registroVentas) {
            html += `<h3>Ventas de ${usuario}</h3><ul>`;
            registroVentas[usuario].forEach(venta => {
                html += `
                    <li>
                        Número de Boleta: ${venta.numeroBoleta}<br>
                        Fecha: ${new Date(venta.fecha).toLocaleString()}<br>
                        Total: $${venta.total.toFixed(2)}<br>
                        Medio de Pago: ${venta.medioPago}<br>
                        Forma de Pago: ${venta.formaPago}
                    </li>
                `;
            });
            html += '</ul>';
        }
        registroDiv.innerHTML = html || '<p>No hay ventas registradas.</p>';
    }

    function mostrarAdminTurnos() {
        const registroTurnos = JSON.parse(localStorage.getItem('registroTurnos'));
        const registroDiv = document.getElementById('adminRegistroTurnos');
        let html = '<ul>';
        registroTurnos.forEach(turno => {
            html += `
                <li>
                    Usuario: ${turno.usuario}<br>
                    Fecha de apertura: ${new Date(turno.fechaApertura).toLocaleString()}<br>
                    Fecha de cierre: ${turno.fechaCierre ? new Date(turno.fechaCierre).toLocaleString() : 'Turno abierto'}
                </li>
            `;
        });
        html += '</ul>';
        registroDiv.innerHTML = html || '<p>No hay turnos registrados.</p>';
    }
</script>
</body>
</html>
