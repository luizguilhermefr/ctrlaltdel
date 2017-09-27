# Ctrl + Alt + Del ⌨️ 🇧🇷

Ctrl + Alt + Del ⌨️ é uma linguagem de programação baseada em [emojis](https://pt.wikipedia.org/wiki/Emoji). Seu nome deriva da clássica sequência de teclas do MS Windows usada em situações onde a máquina não responde como esperado, gerando impaciência e ódio.

## Recursos

A Ctrl + Alt + Del ⌨️ é baseada em emojis. Isso não significa que todo o seu código é construído em torno de emojis, apenas as palavras e expressões reservadas. O usuário ainda pode livremente fazer uso de variáveis, strings e demais recursos utilizando caracteres comuns do seu teclado.

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

## Guia rápido

| Símbolo  | Significado |
| ------------- | ------------- |
| 🌞 | Início do programa |
| 🌚 | Fim do programa |
| ✍️ | E/S Escrever em tela |
| 📰 | E/S Ler do teclado |
| ➕ | Soma |
| ➖ | Subtração |
| ✖️ | Multiplicação |
| ➗ | Divisão |
| 😂 | Tipo de dado inteiro |
| 😋 | Tipo de dado caractere |
| 😎 | Tipo de dado ponto flutuante |
| 😙 | Tipo de dado ponto flutuante de dupla precisão |
| 😣 | Tipo de dado cadeia de caracteres |
| 👉 | Laço de repetição do tipo "para" |
| 👇 | Início de laço do tipo "faça enquanto" |
| 👆 | Fim do laço do tipo "faça enquanto |
| ✋ | Terminar laço (break) |
| 🤔 | Condicional Se ... |
| 👍 | Delimitador inicial de bloco |
| 👎 | Delimitador final de bloco |
| 😠 | Condicional Senão |
| 😖 | Condicional Senão Se (else if) |
| 🚬 | Comentários de linha única|
| > | Maior que |
| < | Menor que |
| ⤴️ | Maior ou igual que |
| ⤵️ | Menor ou igual que |

## Exemplos

Ler dois valores inteiros e retornar o maior deles.

```
🌞                                🚬 início do programa
  😂 x1, x2;                      🚬 declaração de variáveis
  ✍️ "Informe o primeiro valor";  🚬 saída de dados em tela
  📰 x1;                          🚬 entrada do dado x1
  ✍️ "Informe o segundo valor";   🚬 saída de dados em tela
  📰 x2;                          🚬 entrada do dado x2
  🤔 (x1 ⤴️ x2) 👍                 🚬 se x1 maior ou igual que x2, então
    ✍️ x1;                        🚬 saída de dados em tela
  👎 😠 👍                          🚬 senão
    ✍️ x2;                        🚬 saída de dados em tela
  👎                              🚬 fim se
🌚                                🚬 fim do programa

```
