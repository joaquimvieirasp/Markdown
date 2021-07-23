# Título

## Aprendendo Markdown

Existem **6 níveis de tamanho** de título no markdown, assim como no html, para cada tamanho deve se seguir da seguinte forma:

## 1. Títulos.

Para definir o tamanho do título deve se colocar antes do texto o jogo da velha ou cerquilha, #, ##, ###, ####, #####, ######

# Título 1 
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

## 2. Texto em negrito.

Deve se utilizar 2 ** ou 2 __ no inicio e no fim da palavra ou texto, ex:

**texto em negrito**

__texto em negrito__

## 3. Texto itálico.

Deve se utilizar 1 * ou _ no começo e no fim da palavra ou texto, ex:

*texto em itálico*

_texto em itálico_

## 4. Negrito e Itálico.

Deve se utilizar 3 (***) ou 3 (___), ou podemos mesclar * e _, podemos mesclar da seguinte forma utilizando 2 ** e 1 _, ou 2 __ e 1 *, exs:

***texto negrito e itálico***

_**texto negrito e itálico**_

__*texto negrito e itálico*__

## 5. Riscar uma palavra.

Deve se utilizar 2 (~~) antes e depois da palavra, ex:

~~texto riscado~~

## 6. Abrir um bloco de sitação

Deve se colocar o sinal de maior (>) antes do paragrafo, ex:

> **Exemplo** *de bloco de sitação*

## Linhas horizontais.

Exemplo 1, pode se colocar 3(***), abaixo do paragrafo, como no exemplo abaixo
*** 
___
Exemplo 2, pode se colocar 3 (* * *) com espaços ou 3 (_ _ _), como no exemplo abaixo:
* * *
_ _ _
Exemplo 3, pode se colocar vários astersicos a partir do terceiro ou underline, que o markdown já identifica como linha horizontal, como no ex:
*********
_________
## 6. Lista não ordenada

Para criar uma lista não ordenada, basta utilizar o asterisco ou o sinal de +, ou sinal de - antes do item,

Exemplo de como criar uma lista ordenada, ex:

* Item 01
    - sub item 01
    - sub item 02
* Item 02
* Item 03

## 7. Lista ordenada

Para criar uma lista ordenada basta colocar o número seguido de ponto final + espaço e o nome do item, ex:

  1. item 01
  2. Item 02
  3. Item 03

**detalhe** o markdown considera a lista ordenada em ordem crescente, portanto se você colocar uma ordem fora da sequencia o markdown vai desconsiderar e sua numeração e colocar na ordem crescente, como no exemplo abaixo:

Exemplo 1

  1. item 01
  4. Item 02
  5. Item 03

Exemplo 2, colocando a númeração desejada

Campeões da Copa do mundo.

1994\. Brasil  
1998\. França  
2002\. Brasil  

Para colocar a numeração desejda, deve se colocar uma barra invertida seguida do ponto final + espaço, seguida do nome desejado

## 8. Transformar texto em link.

Para transformar um texto em link, utilizamos os colchetes[] e os (), dentro dos colchetes colocamos o texto que vai ser exibido no link e dentro dos paranteses colocamos o endereço (url), ex:

[Aprenda Markdown]
(https://www.udemy.com/course/aprenda-markdown)

Pode se colocar um texto alternatico ao link, basta colocar entre "" o nome do texto como no exemplo:

[Aprenda Markdown]
(https://www.udemy.com/course/aprenda-markdown "aprenda markdown")

## 9. Inserindo imagens.

Para adicionar imagens deve colocar os [ ] os (), assim como como criar os links a diferença aqui é que devemos colocar o sinal de exclamação antes dos colchetes [ ], a sintaxe deve vir dessa forma ![nome da imagem] (endereço da imagem), exemplo:

![Markdown](Markdown.png)

Outro exemplo é criar variavel para adicionar imagens, por exemplo:

Crie a variavém entre [nome da variável]: endereço da imagem, exemplo:

![Markdown][image]
[image]: Markdown.png






























