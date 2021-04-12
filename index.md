<!DOCTYPE html>
<html>
<meta name="viewport" content="width=device-width, initial-scale=1">

<head>
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Raleway&family=Rancho&display=swap" rel="stylesheet">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<link href="formulario.css" rel="stylesheet">
<main>



  <div class="container">
    <title>Formulário de pesquisa</title>


<body>
      <h1 class="title-top" id="title">Formulário de pesquisa</h1>
      <p class="p1" id="description">Obrigado por responder o nosso formulario</p>
      <div class="completo">
        <form id="survey-form">
          <div class="row">
            <div class="form-group">
              <label class="form-group " for="name" id="name-label">
                Nome:</label>
            </div>
            <div class="inputName">
              <input id="name" type="text" required placeholder="Digite seu nome">
            </div>
          </div>
          <div class="row">
            <div class="label2">
              <label for="email" id="email-label">
                Email: </label>
            </div>
            <div class="imputEmail">
              <input id="email" type="email" required placeholder="Digite seu Email">
            </div>
          </div>

   <div class="row">
            <div class="label3">

   <label for="number" id="number-label">
                Idade<span> (opcional) </span></label>
            </div>
            <div class="inputIdade">
<input id="number" type="number" min=18 max=100 required placeholder="idade">
            </div>
          </div>

  <div class="row">
            <div class="label4">

   <label for="dropdown">
              </label>
              <div class="estilo"> seu estilo de jogo favorito?</div>
            </div>
            <div class="selecao">
              <select id="dropdown" name="cores">
                <option value="rpg">
                  Rpg</option>
                <option value="tiro">
                  Tiro</option>
                <option value="estratégia">
                  Estratégia</option>
                <option value="moba">
                  Moba</option>
                <option value="luta">
                  Luta</option>
              </select>
            </div>

<div>
              <p class="estilo">Você ja jogou algum desses jogos? </p>
              <label>
                <input class="centro" id="lol" value="lol" type="radio" name="lol-cod-wow-kof-nda">
                League of Legends</label>

 <label>
                <input class="centro" id="cod" value="cod" type="radio" name="lol-cod-wow-kof-nda">
                Call of Duty</label>


  <label>
                <input class="centro" id="wow" value="wow" type="radio" name="lol-cod-wow-kof-nda">
                World of Warcraft</label>

   <label>
                <input class="centro" id="kof" value="kof" type="radio" name="lol-cod-wow-kof-nda">
                The king of Fighters</label>

<label>
                <input class="centro" id="nda" value="nda" type="radio" name="lol-cod-wow-kof-nda">
                Nenhum</label>
            </div>
            <div>
              <p class="estilo">
                Você se considera um: </p>
              <label>
                <input class="centro" id="pro" value="pro" type="checkbox" name="pro-noob-casual">
                Pro Player</label>

 <label>
                <input class="centro" id="noob" value="noob" type="checkbox" name="pro-noob-casual">
                Noob</label>
              <label>
                <input class="centro" id="casual" value="casual" type="checkbox" name="pro-noob-casual">
                Casual</label>
            </div>
            <div>
              <p class="estilo">Algum comentario ou sugestão?</p>
              <textarea id="comentarios" class="input-textarea" name="comment"
                placeholder="Coloque seu cometario aqui..."></textarea>
            </div>

  <div>
              <button class="yellow-with-darkyellow" type="submit" id="submit">
                Enviar
              </button>
            </div>

</form>




 </body>
  </div>
</main>

</html>
