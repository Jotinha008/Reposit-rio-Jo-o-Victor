<!DOCTYPE html>
<html>
<head>
  <title>Exemplo jQuery</title>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <script>
    $(document).ready(function() {
      
      $("#botao").click(function() {
        
        $("#mensagem").text("Você clicou no botão!").css("background-color", "yellow");
      });
    });
  </script>
</head>
<body>
  <h2 id="mensagem">Clique no botão abaixo</h2>
  <button id="botao">Clicar</button>
</body>
</html># Reposit-rio-Jo-o-Victor
Criado pelo João Victor Rodrigues
