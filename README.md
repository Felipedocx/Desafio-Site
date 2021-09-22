Desafio Proposto pela disciplina de Programação WEB do Centro Universitário de João Pessoa, ministrada pelo Prof. Angelo Gonçalves.
O desafio consiste em criar um site com apenas a página HOME (index.html) em HTML, escolher um determinado tema e fazer uso das tags dentro do tema escolhido.

Tags que podiam ser escolhidas:

1) Estrutura básica;

2) Headings;

3) Parágrafo;

4) Encoding;

5) Negrito;

6) Itálico;

7) Quebras de Linhas;

8) Linhas Horizontais;

9) Listas ordenadas e não ordenadas;

10) Links;

11) Formulários (Atributos e Elementos).




<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">

    <title>Consistência nos aportes é a Chave</title>
</head>

<body>

   <ul  id="ordenedlist">



      <li id="element1"> <h1> Invista Todos os Meses! </h1> </li>

       <li> <p> <b>Aprenda a técnica baseada em aporte mensal de investimento conhecida nos EUA como:</b> <i>Dollar Cost Averaging</i> <b> <br />de
                forma simples;</b>  <p> </li> 

       <li><h2> O investidor só precisa aportar a mesma quantia no ativo que ele deseja <b> mensalmente; </b> </h2></li> 

       <li><h3>Basta ter disciplina e foco;</h3>    </li>

       <li><h4>Com isso forma-se um preço médio de cada investimento;</4></li>
       
       <li><h5>Mais informações clique no link subsequente:</li></h5>

       <li>Disclaimer: informações em inglês</li>


    </ol>
    
    <hr/>
    
    <a href= "https://www.investopedia.com/terms/d/dollarcostaveraging.asp">investopedia</a>
   
   <form autocomplete="on">
    <label for="Escolha a data e hora do seu aporte mensal:"id="datatimelabel">Escolha a data e hora do seu aporte mensal:</label>
    <input type="datetime-local" id="datatempo" name="datetime-local"/> 




</form>

 <hr />








</body>

</html>
