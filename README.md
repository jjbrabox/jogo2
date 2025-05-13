# jogo2
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jogo Simples</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        #gameArea {
            width: 300px;
            height: 300px;
            background-color: lightblue;
            margin: 0 auto;
            border: 2px solid black;
            display: none;
        }
    </style>
</head>
<body>

    <h1>Bem-vindo ao Jogo Simples!</h1>
    <p>Clique no link abaixo para iniciar o jogo:</p>
    
    <!-- Link para iniciar o jogo -->
    <a href="javascript:void(0);" onclick="iniciarJogo()">Iniciar Jogo</a>
    
    <!-- Área do jogo -->
    <div id="gameArea">
        <h2>Você está jogando!</h2>
        <p>Clique em qualquer lugar para continuar...</p>
    </div>

    <script>
        // Função para iniciar o jogo
        function iniciarJogo() {
            document.getElementById('gameArea').style.display = 'block'; // Exibe a área do jogo
            alert("Jogo Iniciado! Clique dentro da área para interagir.");
        }
    </script>
    
</body>
</html>
