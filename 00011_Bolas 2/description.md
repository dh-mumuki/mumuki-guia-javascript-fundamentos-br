Algo interessante sobre nossos tabuleiros é que em suas casa podemos colocar qualquer número de bolas de qualquer cor.

Por exemplo, se tivermos este tabuleiro:


<gs-board>
  GBB/1.0
    size 5 2
    head 3 1
</gs-board>

e executamos o seguinte programa:

```gobstones
program {
  Colocar(Vermelho)
  Colocar(Vermelho)
  Colocar(Azul)
  Colocar(Verde)
  Colocar(Vermelho)
}
```

A garra colocará na casa atual, três bolas vermelhas, uma azul e outra verde.

> Escrevi este programa no editor e veja como está no tabuleiro!
