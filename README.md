<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Ya te pidieron ser su San Valentín?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-image: url('https://www.wallpapertip.com/wmimgs/66-667347_roses-wallpaper-hd.jpg'); /* Fondo de rosas */
            background-size: cover;
            background-position: center;
            padding: 50px;
            transition: all 1s ease;
            color: white;
        }
        #mensaje {
            display: none;
            font-size: 18px;
            color: white;
            background: rgba(0, 0, 0, 0.5); /* Para mejorar la legibilidad */
            padding: 20px;
            border-radius: 15px;
            max-width: 80%;
            margin: auto;
        }
        button {
            background-color: #ff4d4d;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 18px;
            cursor: pointer;
            border-radius: 10px;
            margin-top: 20px;
        }
        button:hover {
            background-color: #cc0000;
        }
    </style>
</head>
<body>

    <h1>¿Ya te pidieron ser su San Valentín?</h1>
    <button onclick="mostrarMensaje()">No</button>

    <div id="mensaje">
        <p>
            Espero que sí lo hagan, y si llega a pasar, sabes que tu felicidad es la mía.<br>
            Deborah, fuiste y siempre serás lo mejor que me pudo haber pasado. Dejaste huella en mí, en mi familia y en mi vida.<br>
            Tu nombre está tatuado en mi corazón. Espero que seas feliz pronto, en un lugar donde seas prioridad y no opción.<br>
            Donde te escuchen, donde sonrían al verte llegar, donde seas vos, donde la vida te sepa mucho mejor.<br>
            Donde te hagan sentir especial, donde defiendan tu nombre cuando no estás, donde sepan cómo sacarte una sonrisa.<br>
            Donde piensen en lo mejor para vos, donde sea hogar y, si se puede, donde te den lo que nunca pude darte y te traten mejor de lo que yo pude...<br>
            <strong>Te extrañaré ♥️</strong>
        </p>
    </div>

    <script>
        function mostrarMensaje() {
            document.querySelector("h1").style.display = "none";
            document.querySelector("button").style.display = "none";
            document.getElementById("mensaje").style.display = "block";
            document.body.style.backgroundImage = "url('https://i.pinimg.com/originals/bb/71/62/bb71624b241de60247cb7f9aa32ebea3.jpg')"; /* Fondo de corazones */
        }
    </script>

</body>
</html>
