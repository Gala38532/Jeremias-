<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barbería XYZ</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Barbería XYZ</h1>
        <p>Gestión de Citas</p>
    </header>

    <section id="citas">
        <h2>Citas</h2>
        <p>Seleccione un profesional:</p>
        <select id="profesionales">
            <option value="barbero1">Barbero 1</option>
            <option value="barbero2">Barbero 2</option>
            <!-- Agrega más opciones según tus profesionales -->
        </select>
        <p>Seleccione un horario:</p>
        <input type="datetime-local" id="horario">
        <button onclick="agendarCita()">Agendar Cita</button>
    </section>

    <section id="precios">
        <h2>Precios</h2>
        <!-- Lista de precios -->
        <ul>
            <li>Corte de Pelo - $20</li>
            <li>Afeitado - $15</li>
            <!-- Agrega más servicios y precios -->
        </ul>
    </section>

    <section id="profesionales">
        <h2>Profesionales</h2>
        <!-- Información sobre los profesionales -->
        <ul>
            <li>Barbero 1 - Especialista en cortes modernos.</li>
            <li>Barbero 2 - Experto en afeitados clásicos.</li>
            <!-- Agrega más información según tus profesionales -->
        </ul>
    </section>

    <script src="script.js"></script>
</body>
</html>
