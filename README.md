# App-peluquer-a-

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Gestión de Citas</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="imagen_corporativa.jpg" alt="Logo de la peluquería">
    </header>
    <main>
        <h1>Gestión de Citas</h1>
        <form>
            <label for="tipo-corte">Tipo de Corte:</label>
            <select id="tipo-corte">
                <option value="adulto">Corte para adulto (11€)</option>
                <option value="niño">Corte para niño (menor de 10 años) (9€)</option>
                <option value="jubilado">Corte para jubilado (9€)</option>
                <option value="barba">Corte de barba (7€)</option>
                <option value="corte-barba">Corte de adulto incluida barba (16€)</option>
                <option value="rapado">Rapado (9€)</option>
            </select>
            <br>
            <label for="fecha">Fecha:</label>
            <input type="date" id="fecha">
            <br>
            <label for="hora">Hora:</label>
            <input type="time" id="hora">
            <br>
            <button type="submit">Solicitar Cita</button>
        </form>
    </main>
    <footer>
        <a href="https://calendar.google.com/calendar/r/eventedit?text=Mi%20cita&dates=YYYYMMDDTHHMMSS/YYYYMMDDTHHMMSS&details=Información%20adicional&location=Dirección%20de%20la%20peluquería">Añadir a Google Calendar</a>
    </footer>
</body>
</html>

