# aniversario
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Primer Aniversario</title>
    <style>
        body {
            background-color: #D9B3FF; /* Fondo morado bebé */
            font-family: Arial, sans-serif;
            color: #6A0572; /* Color de las letras que combinan con el fondo */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            flex-direction: column;
        }
        .container {
            text-align: center;
            padding: 20px;
            border: 2px solid #6A0572;
            border-radius: 10px;
            background-color: #F5E6FF;
        }
        .container h1 {
            font-size: 2em;
            margin: 10px 0;
        }
        .container p {
            font-size: 1.2em;
            margin: 10px 0;
        }
        .btn {
            background-color: #6A0572;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
            margin-top: 20px;
        }
        .photos {
            display: none;
            margin-top: 20px;
        }
        .photos img {
            width: 100px;
            height: 100px;
            object-fit: cover;
            margin: 10px;
            border-radius: 10px;
            border: 2px solid #6A0572;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>¡Feliz Primer Aniversario!</h1>
        <p>Un año lleno de amor, risas y momentos inolvidables.</p>
        <p>Gracias por ser parte de mi vida. Por muchos años más juntos.</p>
        <p>Te quiero mucho.</p>
        <button class="btn" onclick="showPhotos()">Iniciar</button>
        <div class="photos">
            <img src="/mnt/data/image.png" alt="Photo 1">
            <img src="/mnt/data/image.png" alt="Photo 2">
            <img src="/mnt/data/image.png" alt="Photo 3">
            <img src="/mnt/data/Imagen de WhatsApp 2024-07-18 a las 23.12.03_816b07df.jpg" alt="Photo 4">
            <img src="/mnt/data/Imagen de WhatsApp 2024-07-18 a las 23.12.08_2e806d85.jpg" alt="Photo 5">
            <img src="/mnt/data/Imagen de WhatsApp 2024-07-18 a las 23.12.08_2ad2181b.jpg" alt="Photo 6">
            <img src="/mnt/data/Imagen de WhatsApp 2024-07-18 a las 23.12.09_38314588.jpg" alt="Photo 7">
            <img src="/mnt/data/Imagen de WhatsApp 2024-07-18 a las 23.12.09_a9c39907.jpg" alt="Photo 8">
        </div>
    </div>
    <script>
        function showPhotos() {
            document.querySelector('.photos').style.display = 'block';
        }
    </script>
</body>
</html>
