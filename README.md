<!DOCTYPE html>
<html>
<head>

<body> 
  <h2>Seja bem-vindo à minha página Web.</h2>

  <p>Esta é uma página HTML.</p>
  <p><i>Este texto está no formato itálico.</i></p>
  <p>Podemos modificar o conteúdo!</p>
  <p><strong>O que acha de negrito?</strong></p>
  <p><i><strong>Podemos ter as duas opções também, se achar melhor.</strong></i></p>

  <hr>
  
  <h2>Mas afinal, o que é uma página HTML?</h2> 
  <p>Uma página HTML não é uma linguagem de programação, mas sim uma linguagem de marcação para estruturar o conteúdo da página web. Junto ao CSS (design da página) e ao JavaScript    (interação do usuário com a página), teremos algo bonito e interativo.</p>  

<hr>

<h2> Tabela de comparação </h2>

<table width="100%" border="1">
<thead>

<tr>
 
<td> HTLML </td> 
<td> Estrutura </td>
</tr> 

<tr>
<td> CSS </td> 
<td> Estilização </td> 
</tr>

<tr>
<td> JavaScript </td>
<td> Interação </td> 
</tr> 

<tbody>

<tfoot> 
<tr> 
<th colspan="2"> <b>OBS:</b> HTML não é linguagem de programação, mas CSS e JavaScript são.</th>
</tr> 

</tfoot> 
</table> 

<hr>

  <h2>Mas o que é uma página web?</h2>
  <p>Uma página web é a resposta do servidor para o usuário. Exemplo: quando você (usúario) envia ao Google (servidor) alguma pergunta ou simples busca e ele retorna com a página da Wikipédia, a própria Wikipédia é uma página web.</p>

  <hr> 

<p>Formulário de contato</p>


<h2> Fomulário básico HTML </h2> 


<form action="#" method="post"> 

<label for="nome"> Insira Seu nome: </label> 
<input type="text" id="nome" name="nome"required> 

<br>

<label for="email"> E-mail:</label> 
<input type="email" id="email" name="E-mail"required>

<br>

<label for="tel"> Telefone:</label>
<input type="tel" id="tel" name="telefone" required> 

<br>

<label for="nascimento"> Data de Nascimento: </label>
<input type="date" id="nascimento" name="nascimento" required> 

<br>

<fieldset>

<legend> Fale Conosco </legend> 
<label for="msg"> Mensagem a ser enviada: </label><br>
<textarea id="msg" name="mensagem" rows="4" cols="30"></textarea>
</fieldset>

<br>

<button type="submit"> Envie sua mensagem </button> 
<button type="reset"> Limpe caixa de mensagem </button> 

</form> 

<hr>

  <p><i><strong>Bom, essa é minha segunda página web. A primeira foi o famoso "Olá mundo"😁. Espero que tenha gostado.</strong></i></p>

</body>
</html>
