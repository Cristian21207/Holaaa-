<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Te Amo, Elizabeth</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;400&display=swap');

        body {
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(to bottom, #f8cdda, #1c92d2);
            color: white;
            text-align: center;
            overflow: hidden;
        }

        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            padding: 20px;
        }

        h1 {
            font-family: 'Great Vibes', cursive;
            font-size: 4em;
            margin: 10px;
            color: #fff;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);
        }

        p {
            font-size: 1.5em;
            margin: 20px;
            max-width: 600px;
            line-height: 1.6;
            text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.5);
        }

        .heart {
            font-size: 2.5em;
            color: red;
            animation: beat 1s infinite;
        }

        @keyframes beat {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.2);
            }
        }

        .flowers {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://cdn.pixabay.com/photo/2018/04/20/14/25/flowers-3332292_960_720.png') no-repeat center;
            background-size: cover;
            opacity: 0.3;
            z-index: -1;
        }

        button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 1.2em;
            background: #ff7eb3;
            border: none;
            color: white;
            border-radius: 5px;
            cursor: pointer;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.2);
            transition: background 0.3s ease, transform 0.2s ease;
        }

        button:hover {
            background: #ff5789;
            transform: translateY(-2px);
        }
    </style>
</head>
<body>
    <div class="flowers"></div>
    <div class="container">
        <h1>Te Amo, Elizabeth</h1>
        <p>
            Eres la luz de mis días, la flor que decora mi vida y el motivo por el que sonrío.  
            Hoy y siempre, quiero que sepas cuánto significas para mí.  
            Mi amor por ti es infinito y sincero. <span class="heart">❤</span>
        </p>
        <button onclick="alert('¡Elizabeth, este es solo el comienzo de nuestro hermoso viaje juntos!')">¡Dilo otra vez!</button>
    </div>
</body>
</html>
