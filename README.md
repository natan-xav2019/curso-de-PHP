# Curso de PHP

Este curso e uma playlist do canal do youtube [curso em video](https://www.youtube.com/@CursoemVideo)

link da [playlist](https://www.youtube.com/playlist?list=PLHz_AreHm4dlFPrCXCmd5g92860x_Pbr_)

> Aqui irei fazer resumos do que eu julgo mais importante para desenvolvimento e consultas rapidas.

## Variáveis e constantes

link do [video](https://www.youtube.com/watch?v=eC42d9Rsz3g&list=PLHz_AreHm4dlFPrCXCmd5g92860x_Pbr_&index=20&ab_channel=CursoemV%C3%ADdeo)

Variáveis e constantes so guardão um valor.

Como o nome ja diz as variaveis variam.
E as constantes se mantem.

sintaxe de declaração de variaveis e constante.

``` php
# Variaveis
$nome = "Natan";

echo "Seu nome e $nome.";
# Seu nome e Natan

# Constante
const PAIS = "Brasil";

echo "Seu nome e $nome. Mora no ". PAIS;
#Seu nome e Natan. Mora no Brasil
```

## Tipos Primitivos

link do [video](https://www.youtube.com/watch?v=JFEelabfc1o&list=PLHz_AreHm4dlFPrCXCmd5g92860x_Pbr_&index=21&t=1393s&ab_channel=CursoemV%C3%ADdeo)

Os tipos primitivos são int ou interger, float, double, string e bool.

Em valores boleanos o true e 1 e o valor false e vazio.

int tem algumas tipos numero com bases numricas diferentes

- 0b equivale a base 2 (binária)
- 0  equivale a base 8 (octal)
- 0x equivale a representação base 16 (Hexadecimal)

``` php
$num = 0x1A;
echo "O numero e: $num"; # O numero e: 26
$num = 0b1110;
echo "O numero e: $num"; # O numero e: 14
$num = 017;
echo "O numero e: $num"; # O numero e: 15
```

podemos tambem colocar a quantidade de casas decimais colocando `e` apos o numero escrito e quantidade de casa decimais desejada olhe o exemplo abaixo:

- o tipo dessa variavel sera float

``` php
$num = 3e2;
echo "O numero e: $num"; # O numero e: 300
$num = 3e3;
echo "O numero e: $num"; # O numero e: 3000
```

existe uma função chamada `var_dump($variavel);` ela diz o tipo da variavel que e posto no argumento.

podemos fazer coerção de variaveis

``` php
#coerção para a tipagem inteira.
$num = (int) "940";
var_dump($num); #  int(940)
```