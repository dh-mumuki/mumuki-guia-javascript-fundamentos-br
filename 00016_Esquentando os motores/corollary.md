Agora que combinamos as operações, as coisas ficam um pouco mais complicadas, porque você precisa **cuidar mais da ordem**.

Olhe para o programa que você escreveu:

```puppet
program {
  Poner(Rojo)
  Mover(Este)
  Poner(Negro)
}
```

Sequencialmente

1. coloque uma bola vermelha
1. mova-se para o leste
1. depois coloque uma bola preta

Ou seja: coloque uma bola vermelha na posição inicial e uma bola preta no leste
