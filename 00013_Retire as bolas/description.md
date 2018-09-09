Da mesma forma que se pode dar o comando para "colocar a bola" ("Colocar"), temos uma forma de "retirar a bola" ("Retirar"), que remove exatamente uma bola da cor dada.

Por exemplo, o programa a seguir retira duas bolas vermelhas da posição inicial.

```gobstones
program {
  Retirar(Vermelho)
  Retirar(Vermelho)
}
```
> Sabendo disso, eu escrevi um programa que remove **apenas** a bolinha vermelha deste tabuleiro. **Tenha cuidado!** Preste atenção para a posição da garra.: wink:

<gs-board>
  GBB/1.0
    size 2 2
    cell 1 0 Rojo 1
    cell 1 1 Negro 1
    head 1 1
</gs-board>
