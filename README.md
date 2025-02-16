<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eu te amo, minha princesa ❤️</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #ffe6f2;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .heart {
            width: 100px;
            height: 100px;
            background-color: red;
            position: relative;
            transform: rotate(-45deg);
            animation: heartbeat 1s infinite;
        }
        .heart:before,
        .heart:after {
            content: "";
            width: 100px;
            height: 100px;
            background-color: red;
            border-radius: 50%;
            position: absolute;
        }
        .heart:before {
            top: -50px;
            left: 0;
        }
        .heart:after {
            left: 50px;
            top: 0;
        }
        @keyframes heartbeat {
            0%, 100% { transform: scale(1) rotate(-45deg); }
            50% { transform: scale(1.2) rotate(-45deg); }
        }
        .message {
            margin-top: 20px;
            font-size: 20px;
            font-weight: bold;
            color: #ff3366;
        }
    </style>
</head>
<body>
    <div class="heart"></div>
    <div class="message">
        Eu te amo minha princesa ❤️<br>
        Você é a razão da minha felicidade!<br>
        Ass: Seu grande amor, Rodrigo
    </div>
</body>
</html>
