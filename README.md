<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="utf-8">
        <title>Vuntura</title>
        <link rel="stylesheet" href="css/normalize.css">
		<link rel="stylesheet" href="css/reset.css">
		<link rel="stylesheet" href="css/grid.css">
	    <link rel="stylesheet" href="css/vuntura.css">
      </head>

     <body>
        <header class="header">
             <section class="head" class="container">
                <a href="http://vuntura.com.br" target="_blank"><img src="img/vuntura.svg" alt="Logo Vuntura"></a>
                 </section>
         </header>

         <section class="home">
                 <div class="container">
                 <ul class="grid-16">
                  <li>Você é fornecedor de garrafas de vidro?</li>
                  <li>Quer aumentar o número de clientes?</li>
                  <li>A Vuntura pode ajudar!</li>
                 </ul>
                </div>
         </section>
   
   
    <section class="topicos container">
        <div class="lista grid-8">
            <h2>O que estamos oferecendo:</h2>

            <ul class="topico">
            <li>
                <h3>Maior visibilidade</h3>
                    <p>Exiba suas garrafas em nosso site.</p>
            </li>
               
                 <li>
                     <h3>Mais clientes</h3>                       
                         <p>Aumente o seu alcance no mercado de venda de garrafas.</p>
            
                  <li>
                      <h3>Logística simplificada</h3>
                         <p> Nos comprometemos a oferecer uma logística Otimizada, Sustentável e Simplificada para o seu negócio.</p>
                  </li>
                 </ul>	
           </div>
				<div class="formulario container">
					<form id="formulario-dados" method="POST" actin="./enviar.php" class="form grid-7 formphp">
						<label for="name">Nome da Empresa</label>
						<input type="text" id="name" name="nome" required>
						<label for="email">E-mail</label>
						<input type="email" id="email" name="email" required>
						<label for="telefone">Telefone</label>
                        <input type="telefone" id="telefone" name="telefone" required>
                      
                        <label class="nao-aparece"> Se você não é um robô, deixe em branco</label>
                        <input type="text" class="nao-aparece" name="leaveblank">
                        <label class="nao-aparece">Se você não é um robo, não mude este campo.</label>
                        <input type="text" class="nao-aparece" name="dontchange" value="http://">
                       
                        <label for="mensagem">Mensagem</label>
						<textarea id="mensagem" name="mensagem" required></textarea>
						<button id="enviar" name="enviar"  type="submit" class="btn"onclick="funcao1()" value="Exibir Alerta">Enviar</button>
                 	</form>
				</div>
<!-- JavsCript-->
               <script>
                   function funcao1()
                   {
                       alert("E-mail enviado!");
                   }
               </script>

          <!-- JavsCript-->

        </section>

        <footer>
            <div class="rodape container">
            <p>Todos os  direitos reservados. Vuntura 2022</p>
            </div>
        </footer>


    </body>


    
</html>
