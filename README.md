# atividade-faculdade
# Auto detect text files and perform LF normalization
* text=auto<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Primeiro Projeto</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Olá, Mundo! 🌎</h1>
    <p>Esse é meu primeiro projeto no GitHub!</p>
    <button onclick="mostrarMensagem()">Clique em mim</button>

    <script src="script.js"></script>
</body>
</html>body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin-top: 50px;
    background-color: #f4f4f4;
}

h1 {
    color: #333;
}

button {
    padding: 10px 20px;
    background-color: #008CBA;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #005f73;
}function mostrarMensagem() {
    alert("Parabéns! Você acabou de rodar seu primeiro projeto no GitHub 🚀");
}