# Ativ.sla
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastre-se !</title>
</head>
<body>

    <style>
        header {
          background-color: #333;
          color: #fff;
          display: flex;
          justify-content: space-between;
          padding: 20px;
          width: 100%;
          position: fixed;
          top: 0;
          left: 0;
          z-index: 999;
        }
      
        #logo {
          font-size: 24px;
          font-weight: bold;
        }
    
        nav {
          text-align: center;
        }
        nav a {
          color: #fff;
          margin-right: 60px;
          text-decoration: none;
          text-transform: uppercase;
        }
      
        nav a:hover {
          color: #ddd;
        }
      </style>

    </head>
    <body>
      <header>
        <div id="logo">PlaingBasquet</div>
        <nav>
          <a href="index.html">Início</a>
          <a href="Sobre.html">Sobre</a>
          <a href="Loja.html">Cadastro</a>
          <a href="Login.html">Login</a>
          <a href="Loja.html">Loja</a>
        </nav>
      </header><br><br><br><br>
      <h2>Cadastre-se para ter acesso antecipado de eventos e de novidade !</h2><br><br>
      <form method="POST" action="cadastro.php">
        <label for="nome">Nome:</label>
<input type="text" id="nome" name="nome">

<label for="email">E-mail:</label>
<input type="email" id="email" name="email">

<label for="senha">Senha:</label>
<input type="password" id="senha" name="senha">

<label for="confirmar-senha">Confirmar senha:</label>
<input type="password" id="confirmar-senha" name="confirmar-senha">




<button type="submit">Cadastrar</button>

      </form>
      
    
</body>
</html>
