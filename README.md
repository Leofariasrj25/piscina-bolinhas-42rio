# Desafios da Piscina de Bolinhas 42|Rio
## Round #2

Olá a todos, aqui segue os desafios do Round #2 da "piscina de bolinhas" do discord da 42|Rio 
Está semana são mais 5 desafios (4 fáceis e 1 intermediário) abrangendo diversos tópicos
Os desafios agora tem uma seção de descrição e objetivo, conferindo assim um contexto e motivação por trás do desafio.

A partir deste round temos mais uma mudança:
- Novos rounds irão continuar começando as segunda-feiras entre 17:00-18:00
- A data limite para publicação dos desafios de domingo passou para segunda-feira até 12:00

Ou seja 
- o Round #2 está se iniciando hoje 03/08/2021 (data da publicação) (sim, estou atrasado)
- soluções serão aceitas até 12:00 do dia 09/08/2021

### Novidade:
O rank está disponível! para acessar clique [aqui](https://docs.google.com/spreadsheets/d/1Db7txuJBk6sbNo6mtYWjSqNMNdRu9JoyHZy_PkDuDr8/edit?usp=sharing) meu muito obrigado a todos que participaram do Round #1!

Aqueles que perderam o round #1 (ou que não conseguiram fazer todos os desafios) e desejam participar podem fazer o desafios do round #1 e postar a solução + prova no canal #desafios do discord da 42|Rio. Lembrando que a pontuação para soluções postadas após o termino do respectivo Round é de 0,5 ponto para desafios de nível fácil e 1 ponto para o nível intermediário. 

Não é necessário ter feito os rounds anteriores para participar deste.

Para a descrição de regras, motivação por trás da iniciativa, etc. clique [aqui](https://tinyurl.com/piscina-bolinhas42)

## Desafio 1 - Contador de Vogais (fácil - 1 ponto)
### Descrição e Objetivo
Este é um problema simples para lhe introduzir ao processamento de strings, além disso você estará praticando o uso de estruturas condicionais encadeadas e o uso de estruturas de repetição para lidar com dados sequenciais.

Lhe serão dadas várias linhas de texto - e para cada linha desejamos saber o número de vogais.
(a, e, i, o, u, y). nota: y é considerado como vogal para o propósito deste desse desafio.

Parece simples e bobinho mas esta é uma técnica é importante em estratégias de quebra de ciphers de criptografia. um destes é o Caesar Cipher

### Input
>n - o número de linhas que serão inseridas

>linhas contendo caracteres minúsculos (caixa baixa) em português e espaços

### Output
>Deve conter o número de vogais em cada linha, separado por espaços

### exemplo
>4 

>abracadabra 

>pear tree 

>o a kak ushakov lil vo kashu kakao 

>my pyx 

>answer: 

>5 4 13 2 


## Desafio 2 - Protegido por Senha (fácil - 1 ponto)
### Objetivo e Descrição
Senhas, as essenciais e problemáticas senhas. 

O objetivo é criar um programa que é protegido por senha e que não irá abrir ao menos que o usuário e senha corretos sejam passados. Este desafio, assim como o #1 irá requerer conhecimento de laços e condicionais.

### Bônus
>bônus 1: faça com que o usuário e senha sejam armazenados em um arquivo de texto separado

>bônus 2: mostre uma forma de hackear o seu próprio programa


## Desafio 3 - FizzBuzz (fácil - 1 ponto)
### Objetivo e Descrição

Uma rápida pesquisa no google irá lhe mostrar que este é, sem sombra de dúvidas o teste mais famoso de programação na face da terra e que também é, por incrível que pareça, um dos desafios onde as pessoas mais erram. O erro não é pela dificuldade e sim pela simplicidade. Programadores são seres que adoram complicar as coisas, pior, menosprezam o básico e provado em favor de soluções mirabolantes que não sobrevivem o primeiro contato com a realidade. Vamos cortar esse mal pela raiz. 

Imprima todos os números de 0 a 100. 
Para todo número divisível por 3 imprima "Fizz" no lugar do número
Para todo número divisível por 5 imprima "Buzz" no lugar do número
Para todo número que seja divisível por 3 e 5 imprima "FizzBuzz" no lugar do número

>bônus: tente fazer o fizzbuzz da forma mais simples e óbvia possível mas sem usar o operador %

## Desafio 4 - Soma dos dígitos (fácil - 1 ponto)
### Descrição e Objetivo

Este desafio é feito pra lhe introduzir ao básico de sistemas numéricos. Vamos começar aprendendo este conceito ao brincar com o sistema decimal que usamos todos os dias (note que internamente o computador não o usa - ele converte para decimal quando é para mostrar para o usuário)

Todo número maior do que 9 é representado por vários dígitos, sendo assim nós podemos calcular a soma destes dígitos.  Por exemplo, para os números 1984 e 1776 nós temos:

> 1 + 9 + 8 + 4 = 22

> 1 + 7 + 7 + 6 = 21

Neste desafio lhe serão dados diversos números e você irá precisar calcular a soma de seus respectivos dígitos.

**importante** Enquanto muitas linguagens de programação possuem funcionalidades já prontas que convertem de número para string(da qual podemos extrair os dígitos) você não dever usar este artifício (ou similares) já que o objetivo é aprender um novo truque de programação.

**Ao invés disso** você deve usar a divisão por 10 (a base do sistema numeral) repetidas vezes e somar os restos.

### Input
>- A primeira linha deve conter o número (N) de valores a serem processados-
>- E então n linhas irão seguir descrevendo os valores (A B C) que devem ser calculados
>- para cada linha multiplique A por B e adicione C (A * B + C) e então calcule a soma dos dígitos deste resultado. 

### Output
> Reposta deve conter N resultados, separados por espaços.

### Exemplo
>input

>3

>11 9 1

>14 90 232

>111 15 111

>output

>1 16 21

## Desafio 5 - Fibonacci (intermediário - 3 pontos)
### Descrição e Objetivo

A sequência de Fibonacci é composta por uma sucessão de números descrita pelo famoso matemático italiano Leonardo de Pisa (1170-1250), mais conhecido como Fibonacci, no final do século 12. O matemático percebeu uma regularidade matemática a partir de um problema criado por ele mesmo.

A sequência de Fibonacci é famosa pois é um padrão que está presente em diversos lugares na natureza (girassóis, furacões, etc), também é aplicada diariamente no mercado financeiro, na computação (fundação de diversos algoritmos) e nas artes (vide a mona lisa de Leonardo DaVinci)

Seu objetivo é computar os 50 primeiros números da sequência Fibonacci.

>bônus 1: use recursão
