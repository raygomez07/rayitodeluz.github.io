<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para mi Rayito de Luz</title>
    <style>
        body {
            font-family: 'Cursive', sans-serif;
            background: linear-gradient(to bottom right, #ffeb99, #ffbf80);
            text-align: center;
            padding: 20px;
            color: #6e450b;
        }

        h1 {
            color: #ff7f50;
            font-size: 3em;
            margin-top: 50px;
            animation: fadeIn 2s ease-in;
        }

        p {
            font-size: 1.2em;
            color: #4d2600;
            animation: fadeIn 3s ease-in;
        }

        button {
            background-color: #ff6600;
            color: white;
            font-size: 1.5em;
            padding: 15px 30px;
            border: none;
            cursor: pointer;
            border-radius: 50px;
            margin-top: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            transition: all 0.3s ease;
        }

        button:hover {
            background-color: #ff8533;
            transform: scale(1.05);
        }

        #message, #flowers {
            display: none;
            margin-top: 20px;
            animation: fadeIn 1s ease-in-out forwards;
        }

        #message {
            font-size: 2em;
            color: #804000;
        }

        #flowers img {
            width: 350px;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        /* Responsividad para dispositivos móviles */
        @media (max-width: 600px) {
            #flowers img {
                width: 80%;
            }

            button {
                width: 80%;
                font-size: 1.2em;
                padding: 10px 20px;
            }

            h1 {
                font-size: 2.5em;
            }

            #message {
                font-size: 1.5em;
            }
        }
    </style>
</head>
<body>

    <h1>Para mi Rayito de Luz</h1>
    <p>Presiona el botón para descubrir algo especial que tengo para ti.</p>
    
    <button onclick="showSurprise()">¡Te amo! 💖</button>
    
    <div id="message">
        <h2>Feliz 21 de noviembre, Te Amo Rayito de Luz.</h2>
        <p>Atte. Gmez.</p>
    </div>

    <div id="flowers">
        <!-- Imagen de girasoles -->
        <img src="https://media.istockphoto.com/id/187126217/es/foto/girasol-bouquet.webp?s=612x612&w=is&k=20&c=yTayTD8p_TfWwsI5ejxO7Ak9CG8DnwFew4OenLiaakE=" alt="Ramo de girasoles">
    </div>

    <script>
        function showSurprise() {
            document.getElementById("message").style.display = "block";
            document.getElementById("flowers").style.display = "block";
        }
    </script>
</body>
</html>
