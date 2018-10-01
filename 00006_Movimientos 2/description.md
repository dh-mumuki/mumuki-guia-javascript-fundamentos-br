Vamos entender o que acabamos de fazer. Acredite ou não, nós apenas **escrevemos um programa**.

Todo programa tem uma seção de código onde os comandos (ações) que queremos que a máquina execute são declarados. Ao executar um programa, os *comandos* são executados e obtemos um *resultado*.

Na linguagem `Gobstones` esta seção de código é chamada `programa`. Nesta seção, executaremos os comandos que queremos que a máquina execute na placa **inicial** e cujo resultado será exibido na placa **final**.

A sintaxe do `programa` em `Gobstones` é bastante simples:

1. nós escrevemos um comando (linha) que diz `program` (tudo minúsculo), seguido de uma chave de abertura: `{`
1. então os comandos: um em cada linha
1. e finalmente, uma última chave que fecha aquela que abrimos anteriormente: `}`

Alguns exemplos de `program`:

<table class = "table" style = "largura: 100%">
  <tbody>
  <tr>
    <td style = "text-align: left">
      <pre class = "highlight gobstones"> <código> <span class = "kr"> program </ span> {
} </ code> </ pre>
    </ td>
    <td style = "alinhamento de texto: centro"> <i class = "fa fa-arrow-right"> </ i> </ td>
    <td style = "text-align: left">
Não faz nada
    </ td>
  </ tr>
  <tr>
    <td style = "text-align: left">
      <pre class = "highlight gobstones"> <código> <span class = "kr"> program </ span> {
  Mover(Norte)
} </ code> </ pre>
    </ td>
    <td style = "alinhamento de texto: centro"> <i class = "fa fa-arrow-right"> </ i> </ td>
    <td style = "text-align: left">
Mova a garra uma posição para o norte
    </ td>
  </ tr>
  <tr>
    <td style = "text-align: left">
      <pre class = "highlight gobstones"> <código> <span class = "kr"> program </ span> {
  Mover(Norte)
  Mover(Norte)
} </ code> </ pre>
    </ td>
    <td style = "alinhamento de texto: centro"> <i class = "fa fa-arrow-right"> </ i> </ td>
    <td style = "text-align: left">
Mova a garra duas posições para o norte
    </ td>
  </ tr>
  <tbody>
</ table>



> Sabendo disso, eu escrevi um programa que move a cabeça três vezes para o norte, em uma placa de 2x4 com a cabeça na origem (a célula na parte inferior esquerda):

<table class= "table" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Inicial</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Final</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 2 4
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 2 4
        head 0 3
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>
