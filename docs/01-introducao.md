# Módulo 01 - Introdução à linguagem C

## Objetivo do módulo
Neste primeiro módulo, a ideia é entender o que é a linguagem C, por que ela é tão importante no estudo da programação e como um programa simples é organizado.

Ao final da leitura, você deve conseguir:

- entender o papel da linguagem C na computação;
- reconhecer a estrutura básica de um programa;
- identificar bibliotecas, função principal e comandos de saída;
- compilar e executar um primeiro exemplo.

## O que é a linguagem C
A linguagem C é uma linguagem de programação de propósito geral, criada com foco em eficiência, desempenho e controle sobre o funcionamento do programa.

Ela é muito utilizada no ensino de programação porque ajuda a construir uma base sólida em:

- lógica de programação;
- organização de algoritmos;
- uso de memória;
- funcionamento interno dos programas.

Além do contexto acadêmico, C também é usada em:

- sistemas operacionais;
- compiladores;
- sistemas embarcados;
- drivers;
- bibliotecas de alto desempenho.

## Por que aprender C
Aprender C é importante porque ela ajuda a compreender conceitos que aparecem em várias outras linguagens.

Quando estudamos C, desenvolvemos melhor noção de:

- tipos de dados;
- entrada e saída;
- estruturas condicionais;
- estruturas de repetição;
- funções;
- ponteiros e memória.

Isso faz com que o aprendizado de outras linguagens posteriormente se torne mais fácil.

## Estrutura básica de um programa em C
Veja um exemplo simples:

```c
#include <stdio.h>

int main() {
    printf("Ola, mundo!\n");
    return 0;
}
```

Agora vamos entender cada parte.

### `#include <stdio.h>`
Essa linha inclui uma biblioteca padrão da linguagem C.

A biblioteca `stdio.h` permite usar funções de entrada e saída, como:

- `printf()` para mostrar informações na tela;
- `scanf()` para ler dados do teclado.

### `int main()`
A função `main` é o ponto de entrada do programa.

Isso significa que a execução começa nela.

O `int` indica que a função retorna um valor inteiro ao final.

### `{ }`
As chaves delimitam o bloco da função.

Tudo o que estiver dentro delas pertence ao corpo da `main`.

### `printf("Ola, mundo!\n");`
Esse comando exibe uma mensagem na tela.

- `printf` é uma função de saída;
- o texto entre aspas é a mensagem;
- `\n` representa uma quebra de linha;
- o ponto e vírgula `;` indica o fim do comando.

### `return 0;`
Esse comando encerra a função `main` e informa que o programa terminou corretamente.

## Como compilar um programa em C
Depois de escrever o código em um arquivo com extensão `.c`, é necessário compilá-lo.

Se estiver usando `gcc`, um exemplo seria:

```bash
gcc programa.c -o programa
```

Depois, a execução pode ser feita com:

```bash
./programa
```

Em alguns ambientes Windows, a execução pode ser:

```bash
programa.exe
```

## Primeiro exemplo comentado
Veja outro exemplo simples:

```c
#include <stdio.h>

int main() {
    printf("Meu primeiro programa em C.\n");
    printf("Estou aprendendo a estrutura basica da linguagem.\n");
    return 0;
}
```

Esse programa:

- inclui a biblioteca de entrada e saída;
- inicia a função principal;
- mostra duas mensagens;
- termina com sucesso.

## Erros comuns de quem está começando
No início, alguns erros são bastante frequentes:

- esquecer o ponto e vírgula no final de uma instrução;
- escrever `main` de forma incorreta;
- esquecer as chaves;
- não incluir a biblioteca necessária;
- tentar compilar um arquivo com extensão errada.

Esses erros fazem parte do processo de aprendizagem. O mais importante é ler as mensagens do compilador com calma e revisar o código.

## Resumo do módulo
Neste módulo, você viu que:

- C é uma linguagem importante para a base da computação;
- todo programa possui uma estrutura mínima;
- a função `main` é o início da execução;
- `printf` permite exibir mensagens;
- o código precisa ser compilado antes de ser executado.

## Próximo passo
Depois desta introdução, o próximo estudo natural é avançar para conceitos fundamentais, como:

- variáveis;
- tipos de dados;
- operadores;
- entrada e saída.
