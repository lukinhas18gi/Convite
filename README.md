# Convite
Convite romântico 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Convite para Piquenique</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #f7e4e1;
            margin: 0;
        }
        .container {
            text-align: center;
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        h1 {
            color: #b85c5c;
        }
        p {
            font-size: 18px;
            color: #555;
        }
        button {
            background-color: #b85c5c;
            color: #fff;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #9e4a4a;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Convite para um Piquenique Romântico</h1>
        <p>linda, gostaria de te convidar para um piquenique especial. Preparar um momento só para nós dois, cheio de carinho, risadas, e um belo beck.</p>
        <p>O que acha do TG (ou qualquer outro lugar) neste fim de semana?</p>
        <button onclick="confirmarPresenca()">Confirmar Presença</button>
    </div>

    <script>
        function confirmarPresenca() {
            alert("Presença confirmada! Mal posso esperar para nosso piquenique.");
        }
    </script>
</body>
</html>
