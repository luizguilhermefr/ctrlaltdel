# Ctrl + Alt + Del ⌨️ 🇧🇷

Ctrl + Alt + Del ⌨️ é uma linguagem de programação baseada em [emojis](https://pt.wikipedia.org/wiki/Emoji). Seu nome deriva da clássica sequência de teclas do MS Windows usada em situações onde a máquina não responde como esperado, gerando impaciência e ódio.

## Recursos

A Ctrl + Alt + Del ⌨️ é baseada em emojis. Isso não significa que todo o seu código é construído em torno de emojis, apenas as palavras e expressões reservadas. O usuário ainda pode livremente fazer uso de variáveis, strings e demais recursos utilizando caracteres comuns do seu teclado.

Em suma, é uma linguagem simples. Não possui comentários e nem subprogramas, além de possuir poucas estruturas de laços ou saltos condicionais.

Todo o código da linguagem é envolto por um início e fim, a saber, 🌞 e 🌚. Cada programa pode ter apenas um início e fim.

## Origens

Não há nenhuma linguagem orientada a emojis com expressão no mercado. Isso deve-se a dificuldade de escrita dos programas (muito por conta da não existência de um teclado de emojis nativo para computador) e da peculiaridade de tal forma de escrita.

O principal recurso é a economia de espaço dos códigos fonte de um programa. Veja o comparativo de um programa Hello World em Java e Ctrl + Alt + Del ⌨️.

* Java (101 bytes)

```java
class Main {
  public static void main(String[] args) {
    System.out.println("Hello, World");
  }
}
```

* Ctrl + Alt + Del ⌨️ (32 bytes - Alguns emojis possuem 4 bytes, outros 6 bytes)

```
🌞
✍️ "Hello, World";
🌚
```

Se o programador possuir um [teclado de emojis](https://www.google.com.br/search?q=emoji+keyboard), sua vida será ainda mais facilitada.

## Especificação

### Tipos de dados

A linguagem conta com os seguintes tipos de dados:

| Identificador | Significado | Descrição |
| ------------- | ------------- | ------------- |
| 😂 | Tipo de dado booleano | Um byte preenchido com zeros ou uns |
| 😋 | Tipo de dado caractere | Quatro bytes UTF-8 |
| 😎 | Tipo de dado ponto flutuante de dupla precisão | Oito bytes, padrão IEEE-754 |
| 🔠 | Tipo de dado cadeia de caracteres | Uma cadeia de caracteres, é iniciado com 32x4 bytes (32 caracteres) e tem o tamanho aumentado neste mesmo valor sempre que excede este valor, sendo realocado em memória |

### Operadores lógicos, aritméticos e relacionais

Ctrl + Alt + Del ⌨️ não possui muitos operadores. Porém, possui os essenciais para qualquer programa básico:

#### Lógicos

Operadores lógicos tem como entrada dois valores booleanos (exceto o NOT) e retorna um novo valor booleano.

| Identificador | Nome | Significado |
| ------------- | ------------- | ------------- |
| 🤙 | AND | Verdadeiro se ambos valores são verdadeiros |
| 🤞 | OR | Verdadeiro se um ou mais dos valores é verdadeiro |
| 🚫 | NOT | Toma como entrada um valor booleano e retorna o seu inverso |
| 🖕 | XOR | Verdadeiro se um dos valores é verdadeiro e falso se ambos são falsos ou verdadeiros |

#### Aritméticos

Os operadores aritméticos só trabalham com valores em ponto flutuante de dupla precisão, já que este é o único tipo de dado disponível na linguagem.

| Identificador | Nome | Significado |
| ------------- | ------------- | ------------- |
| ➕ | Soma | Soma dois valores numéricos (*double*) |
| ➖ | Subtração | Subtrai, do valor numérico a esquerda, o valor numérico da direita |
| ✖️ | Multiplicação | Multiplica dois valores numéricos |
| ➗ | Divisão | Divide o valor numérico da esquerda pelo valor numérico da direita |

#### Relacionais

Os operadores relacionais tem como entrada dois valores numéricos e retornam um valor booleano. Os operadores "igual" e "diferente" também se aplicam a caracteres (não cadeias). O operador "igual em tamanho" se aplica somente a cadeias.

| Identificador | Nome | Significado |
| ------------- | ------------- | ------------- |
| 🤜 | Maior que | Verdadeiro se o valor da **esquerda** é maior que o da direita |
| 🤛 | Menor que | Verdadeiro se o valor da **esquerda** é menor que o da direita |󠀽󠀽
| 👩‍❤️‍💋‍👩 | Igual | Verdadeiro se ambos os valores são verdadeiros ou falsos |
| ⚔️ | Diferente | Verdadeiro se um dos valores é verdadeiro e outro é falso |
| 👥 | Igual em tamanho | Verdadeiro se ambas as cadeias possuem o mesmo tamanho |

### Atribuição

A atribuição depende do tipo de dado declarado, não há atribuição entre diferentes tipos de dados. O operador de atribuição é o 🤘.

| Destino | Origem | Sintaxe |
| ------------- | ------------- | ------------- |
| Numérico | Numérico | <variável numérica> 🤘 <variável numérica> |
| Caractere | Caractere | <variável caractere> 🤘 <variável caractere> |
| Booleano | Booleano | <variável booleana> 🤘 <variável booleana> |
| Cadeia | Cadeia | <variável cadeia> 🤘 <variável cadeia> |

### Saltos

Os blocos não são delimitados por chaves, mas pelo início e fim de cada condicional, no estilo "se ... fim-se".

#### Se então

Executa um bloco se a condição for satisfeita. Não existe "senão", para este caso deve ser testado novamente utilizando o operador de negação.

| Símbolo  | Significado |
| ------------- | ------------- |
| 🤔 | Início do bloco condicional |
| 👌 | Fim do bloco condicional |

*Exemplo de código*

```
🤔 (1 🤜 result)
    ...
👌
```

#### Caso

Dado um valor **numérico** ou **caractere**, executa determinado bloco. Os blocos são indicados pela expressão "caso" (👉).

| Símbolo  | Significado |
| ------------- | ------------- |
| 🖐️ | Início condicional |
| ✊ | Fim do bloco condicional |
| 👉 | Indicador de caso |

*Exemplo de código*

```
🖐️ (var)
  👉 1:
       ...
       👊
  ...
  👉 n:
       ...
       👊
✊
```

### Laços de Repetição

Há dois laços de repetição fundamentais na linguagem.

#### Para

O para consiste de uma tupla de <condição de continuidade, expressão>. O bloco é executado sempre que a condição de continuidade é satisfeita e executa a *expressão* (geralmente incremento ou decremento) ao final de cada laço.

| Símbolo  | Significado |
| ------------- | ------------- |
| 🌊 | Declaração do para |
| 💧 | Fim do bloco de para |

*Exemplo de código*

```
😎 i
i 🤘 0
🌊 (i 🤛 10; i 🤘 i ➕ 1)
  ...
💧
```

#### Faça enquanto

O faça enquanto é um laço de repetição com pós condição.

| Símbolo  | Significado |
| ------------- | ------------- |
| 🏄 | Declaração do faça |
| 🏊 | Fim do bloco de faça e declarador da condição de parada |

*Exemplo de código*

```
🏄
  ...
🏊 (i ⚔️ 10)
```

### Variáveis

Os identificadores na linguagem são bastante flexíveis. Pode-se utilizar qualquer caractere ASCII ou emoji em um nome de variável. Não pode-se, contudo, utilizar os emojis reservados. O nome da variável termina com um espaço ou quebra de linha. Isso significa que não há a possibilidade de declarar múltiplas variáveis em uma linha. Também não pode-se assinalar um valor à variável em sua declaração, isso deve ser feito a *posteriori*.

*Exemplo de código*

```
😂 variablesCanHave🐻Emojis
🔠 🎅🔫
```

A atribuição depende do tipo da variável. Cadeias podem receber atribuições por meio de aspas duplas. Caracteres podem ser atribuidos por aspas simples.

*Exemplo de código*

```
😂 🤘 👎
🔠 🤘 "This is some string!"
😋 🤘 'a'
😎 🤘 3.14159
```

### Emojis reservados

| Emoji  | Significado |
| ------------- | ------------- |
| 🌞 | Início do programa |
| 🌚 | Fim do programa |
| ✍️ | E/S Escrever em tela |
| 📰 | E/S Ler do teclado |
| 🌊 | Início do laço de repetição do tipo "para" |
| 💧 | Fim do laço de repetição do tipo "para" |
| 🏄 | Início do laço do tipo "faça enquanto" |
| 🏊 | Fim do laço do tipo "faça enquanto" |
| 🖐 | Início da condicional "caso" |
| 👉 | Identificador de caso |
| ✊ | Fim da condicional "caso" |
| 👊 | "Break", paralisa a execução de um bloco |
| 🤔 | Início condicional "se" |
| 👌 | Fim condicional "se" |
| 😂 | Declaração de dado booleano |
| 😋 | Declaração de dado caractere |
| 😎 | Declaração de dado ponto flutuante de dupla precisão |
| 🔠 | Declaração de dado cadeia de caracteres |
| 👍 | Booleano verdadeiro (`true`) |
| 👎 | Booleano falso (`false`) |
| ❔ | Nulo, sem valor (`NULL`) |

## EBNF

A linguagem é delimitada por um início e fim. Tudo o que estiver fora destes delimitadores será considerado um erro de sintaxe. Portanto, resumidamente:

> `{ }` (chaves) delimitam um bloco opcional, não foi utilizado chaves para não conflitar com [expressões regulares](http://pubs.opengroup.org/onlinepubs/7908799/xbd/re.html).
> `\E`, usado em expressões regulares, neste contexto significa "qualquer emoji".

```
<BEGIN> -> 🌞 <STRUCTURE> 🌚
<STRUCTURE> -> <VARIABLE DECLARATION> {<STRUCTURE>} | <VARIABLE ASSIGNMENT> {<STRUCTURE>} | <LOOP> {<STRUCTURE>} | <CONDITIONAL> {<STRUCTURE} | <IO> {<STRUCTURE}
<VARIABLE DECLARATION> -> <VAR_TYPE> <VAR_NAME>
<VAR_TYPE> -> [😂|😋|😎|🔠]
<VAR_NAME> -> [0-9A-Za-z_\E]¹[0-9A-Za-z_\E]*
<VARIABLE_ASSIGNMENT> -> <VAR_NAME> 🤘 <VALUE>
<VALUE> -> [[👍|👎|❔] | [\d+|\d+.\d+] |  ["\."] | ['\.¹']]
<LOOP> ->
<CONDITIONAL> ->
<IO> -> 
<declaração de variáveis> -> 😂 <id>; | 😋 <id>; | 😎 <id>; | 😙 <id> ; | 😣 <id> ;
<id> -> [A-Za-z]¹[0-9A-Za-z_]* | [A-Za-z]¹[0-9A-Za-z_]*, <id>
<operação de E/S> -> <read> | <write>
<read> -> 📰 <id>;
<write> -> ✍️ <id> ;
```

## Exemplos

Ler dois valores inteiros e escrever o maior deles.

```
🌞
  😂 x1
  😂 x2
  ✍️ "Informe o primeiro valor"
  📰 x1
  ✍️ "Informe o segundo valor"
  📰 x2
  🤔 (x1 🤜 x2)
    ✍️ x1
  👌
  🤔 (🚫(x1 🤜 x2))
    ✍️ x1
  👌
🌚
```
