# paginaWeb
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instrumentos Musicales</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px;
            font-size: 24px;
        }
        .contenedor {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
        }
        .instrumento {
            background: white;
            padding: 15px;
            margin: 10px;
            border-radius: 10px;
            width: 300px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        img {
            width: 100%;
            border-radius: 10px;
        }
    </style>
</head>
<body>

    <header>
        🎶 Instrumentos Musicales 🎵
    </header>

    <div class="contenedor">
        <div class="instrumento">
            <img src="guitarra.jpg" alt="Guitarra">
            <h3>Guitarra</h3>
            <p>Instrumento de cuerdas muy popular en distintos géneros musicales.</p>
        </div>

        <div class="instrumento">
            <img src="piano.jpg" alt="Piano">
            <h3>Piano</h3>
            <p>Instrumento de teclas con un sonido armónico y versátil.</p>
        </div>

        <div class="instrumento">
            <img src="violin.jpg" alt="Violín">
            <h3>Violín</h3>
            <p>Instrumento de cuerdas frotadas con un sonido elegante y melódico.</p>
        </div>
    </div>

</body>
</html>
