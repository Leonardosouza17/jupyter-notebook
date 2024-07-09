# Listas em python

## Definindo uma lista
``frutas = ["abacate", "uva", "melão"]``

1- Objetivo: Criar uma lista chamada frutas.

2- Explicação: A lista legumes contém três strings: "abacate", "uva" e "melão". Uma lista em Python é uma coleção ordenada e mutável que permite a adição, remoção e modificação dos elementos contidos nela.

### Impressão da lista
``print(frutas)``

1- Objetivo: Exibir os elementos da lista frutas.

2- Explicação:  O comando print(frutas) imprime o conteúdo da lista frutas, que neste caso será ['abacate', 'uva', 'melão'].

### Impressão dos dados
``print(type(frutas))``

1- Objetivo: Mostrar o tipo de dado da variável frutas.

2- Explicação: O comando print(type(frutas)) imprime o tipo da variável frutas. Como frutas é uma lista, o resultado será **<class 'list'>**.

## Acessando os itens da lista 
``print(frutas[0])``

``print(frutas[1])``

``print(frutas[2])``

#### 1° Item 
``print(frutas[0])``
1- Objetivo: Exibir o primeiro item da lista frutas.

2- Explicação: Em Python, as listas são indexadas a partir de 0. Assim, **frutas[0]** refere-se ao primeiro item da lista, que é "abacate". O comando print **(frutas[0])** imprime "abacate".

#### 2° Item 
``print(frutas[1])``
1- Objetivo: Exibir o segundo item da lista frutas.

2- Explicação: O índice 1 refere-se ao segundo item da lista. Portanto, **frutas[1]** retorna "uva". O comando print **(frutas[1])** imprime "uva".

#### 3° Item 
``print(frutas[2])``
1- Objetivo: Exibir o terceiro item da lista frutas.

2- Explicação: O índice 2 refere-se ao terceiro item da lista. Assim, **frutas[2]** retorna "melão". O comando print **(frutas[2])** imprime "melão".

### Implementação do Loop **for**

``for fruta in frutas:``

``print(fruta)``


**for fruta in frutas:**

1- Objetivo: Iterar sobre cada item na lista `frutas`.

2- Explicação: A estrutura do loop for em Python permite iterar sobre todos os itens de uma lista (ou qualquer outro iterável). Aqui, fruta é uma variável temporária que assume, a cada iteração, o valor do próximo item da lista frutas.

**print(fruta)**
1- Objetivo: Imprimir o item atual da iteração.

2- Explicação: Dentro do loop, o comando **print(fruta)** é executado em cada iteração. Ele imprime o valor atual de fruta, que é o item da lista fr**utas correspondente à iteração atual.

### Como Funciona
- **Primeira Iteração:** fruta recebe o valor "abacate". O comando **print(fruta)** imprime "abacate".
- **Segunda Iteração:** fruta recebe o valor "uva". O comando **print(fruta)** imprime "uva".
- **Terceira Iteração:** fruta recebe o valor "melão". O comando **print(fruta)** imprime "melão".


## Lista Mista

- Este código exemplifica a criação e impressão de uma lista mista em Python. Uma lista mista é uma estrutura de dados que pode conter elementos de diferentes tipos, como strings, inteiros, números de ponto flutuante e booleanos.

``listaMista = ["notebook", 10, 7.56, True]``

1- **listaMista:** Esta variável é uma lista que contém quatro elementos.

2- **"notebook"**: O primeiro elemento é uma string.

3- **10** O segundo elemento é um número inteiro.

4- **7.56** O terceiro elemento é um número de ponto flutuante (float).

5- **True:** O quarto elemento é um valor booleano.

``print(listaMista)``

1- **print(listaMista):** Esta função imprime o conteúdo da lista listaMista no console. O resultado será: ["notebook", 10, 7.56, True].

### Observações
- A lista mista em Python é flexível e pode conter diferentes tipos de dados, tornando-a útil para armazenar coleções heterogêneas de elementos.
- O uso de diferentes tipos de dados em uma única lista pode facilitar a organização e manipulação de informações diversas em um único local.


## Listas Valores Repetidos

- Este código exemplifica a criação e impressão de uma lista contendo valores repetidos em Python. Listas em Python permitem armazenar múltiplas ocorrências do mesmo valor.

``listaValoresRepetidos = ['teclado', 'teclado', 'teclado', 'teclado']``

1- **listaValoresRepetidos:** Esta variável é uma lista que contém quatro elementos.

2- **'teclado':** Todos os quatro elementos da lista são a string **'teclado'**.

``print(listaValoresRepetidos)``

1- **print(listaValoresRepetidos):** Esta função imprime o conteúdo da lista **listaValoresRepetidos** no console. O resultado será: **['teclado', 'teclado', 'teclado', 'teclado']**.


## Tamanho das Listas

- Este código exemplifica como determinar e imprimir o tamanho de diferentes listas em Python usando a função **len()**. A função **len()** retorna o número de elementos presentes em uma lista.

``frutas = ['abacate', 'uva', 'melão']``

``listaMista = ["notebook", 10, 7.56, True]``

``listaValoresRepetidos = ['teclado', 'teclado', 'teclado', 'teclado']``

- **frutas:** Esta lista contém três elementos, todos strings.
- **listaMista**: Esta lista contém quatro elementos de diferentes tipos (string, inteiro, float e booleano).
- **listaValoresRepetidos**: Esta lista contém quatro elementos, todos iguais a 'teclado'.

``print(len(frutas))  # len -> length``

``print(len(listaMista))``

``print(len(listaValoresRepetidos))``

- **len(frutas)**: Esta função retorna o número de elementos na lista frutas, que é 3.
- **len(listaMista)**: Esta função retorna o número de elementos na lista listaMista, que é 4.
- **len(listaValoresRepetidos)**: Esta função retorna o número de elementos na lista listaValoresRepetidos, que é 4.






 





