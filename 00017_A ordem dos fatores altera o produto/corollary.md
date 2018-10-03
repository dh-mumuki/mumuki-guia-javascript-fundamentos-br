Moral: eles não fazem o mesmo! Mudar a ordem mudou o objetivo, isto é, o ‘o quê’.

O primeiro programa


```gobstones
program {
  Mover(Leste)
  Colocar(Vermelho)
  Colocar(Preto)
}
```
sequencialmente:

1. se move para leste
1. então põe uma bola vermelha
1. então põe uma bola preta

Ou seja, coloque uma bola vermelha e uma bola preta a leste da posição inicial.

Enquanto o segundo programa

```puppet
program {
  Colocar(Preto)
  Mover(Leste)
  Colocar(Preto)
}
```
sequencialmente:

1. Põe uma bola preta
1. Se move para leste
1. Então põe uma bola vermelha

Ou seja: põe uma bola preta na posição inicial e uma bola vermelha a leste da bola preta.