Genial :smile:!!!.

Você já entendeu como mover a garra do tabuleiro usando a operação “Mover” e as direções (Norte, Sul, Leste e Oeste). Vamos um passo além com as “bolinhas”. Em qualquer célula do nosso tabuleiro, podemos colocar "bolinhas". Existem diferentes cores:

Vermelho (‘Vermelho’)
Azul (‘Azul’)
Preto (‘Preto’)
Verde (‘Verde’)



Por exemplo, este é um tabuleiro com uma bola vermelha e uma bola preta:


<gs-board>
  GBB/1.0
    size 2 2
    cell 1 0 Rojo 1
    cell 1 1 Negro 1
    head 1 1
</gs-board>



Além de se mover, a garra também pode colocar bolas na célula onde está. Para isso temos a operação 'Colocar', que diz à garra para depositar uma bola da cor dada:

```gobstones
program {
  Poner(Rojo)    
}
```


> Experimente este programa! Eu escrevi o código no editor e dei a ele ** Enviar ** para ver o que acontece quando eu o executo neste tabuleiro.

<gs-board>
  GBB/1.0
    size 3 3
    head 0 0
</gs-board>
