# veigh


<!DOCTYPE html>
<html lang="PT-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>os guri tao forgano</title>
</head>
<body>
    <script src="script.js"></script>

    Digite um número para o código forgar!!
    <input type="number" id="numero">
    <button onclick="calcular()">calcular </button>
    <p id="resultado"></p>

</body>
</html>


function calcular(){
    
    const n = Number (document.getElementById('numero').value);
    let i = 1, resultado = '';

    
    while (i <= 10) {
        resultado += n + ' x ' + i + ' = ' + (n * i) + '///';
        i++;
    }
    document.getElementById('resultado').innerText = resultado;

}
