index.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Menu de Acessibilidade</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div id="acessibilidade">
    <button onclick="aumentarFonte()">A+</button>
    <button onclick="diminuirFonte()">A-</button>
    <button onclick="alternarContraste()">Alto Contraste</button>
  </div>

  <div id="conteudo">
    <h1>Bem-vindo ao site</h1>
    <p>Este é um exemplo de site com menu de acessibilidade.</p>
  </div>

  <script src="script.js"></script>
</body>
</html>

style.css
body {
  font-size: 16px;
  background: #fff;
  color: #000;
}

#acessibilidade {
  position: fixed;
  top: 10px;
  left: 10px;
  background: #eee;
  padding: 10px;
  border-radius: 5px;
  z-index: 1000;
}

.contraste-alto {
  background: #000 !important;
  color: #fff !important;
}
