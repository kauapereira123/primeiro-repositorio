<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="cabeçalho">
        <img class="cabeçalho-imagem" src="ferrari-logo-brand-car-symbol-with-name-design-italian-automobile-illustration-with-black-background-free-vector.jpg" alt="logo do site">
        <ul class="cabeçalho-lista">
            <li class="cabeçalho-lista-item">ESCOLA</li>
            <li class="cabeçalho-lista-item">ESTUDANTE</li>
        </ul>
    </header>
    <section class="EMPRESA">
        <h2 class="EMPRESA-TITULO">SOBRE A EMPRESA</h2>
        <p class="EMPRESA-texto 1"></p>
        <p class="EMPRESA-texto 2"></p>
    </section>
    
</body>
<h1>oi tudo bem</h1>
</html>

css:

*{
    margin: 0;
    padding: 0;
}

.cabeçalho {
    background-color: #000000;
    color: #ffffff;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 24px 0;
}

.cabeçalho-imagem {
    width: 20%;
}

.cabeçalho-lista-item {
    display: inline-block;
    margin: 0 20px;
    font-size: 24px;
}
