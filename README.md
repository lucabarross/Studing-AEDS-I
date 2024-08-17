# Conceitos Iniciais
  Algoritimos --> Passo a Passo de um solução de um determinado problemas, contendo algumas estruturas: 
  - Narrativa
  - Fluxograma
  - Pseudocódigo / Portugol
  - Código Formatado

## Linguagens de Programação
  Conjuntos de comandos e estruturas, assim como convenções de uso no processo de codificação de uma solução, como:
  - C;
  - C++;
  - C#;
  - Java;

## Computador / Interpretador
  Programa ou software que verifica a sintaxe e a semântica de um código que utilliza determinadas linguagens. Se a verificação for de uma linha apenas, seguida da execulão daquela linha, então, é chamada de interpretador.

## Integrated Development Envirament (IDE)
  Software que integra o editor, o consultador e a execução do código. Como exemplo: 
  - CodeBlocks;
  - Replit;
  - Visual Studio Code (VSCode);

## Arquitetura Computador
  A analise de um problema é a identificação das entradas e saídas do que será processado. Isso é feito antes da codificação.

## Paradigmas da Programação
1) Programação estruturada funcional:
   - Uma programação sequencial (ou em paralela) organizado por funções com os acionamentos necessários; 
2) Programação Orientada por Objetos (POO):
   - Uma programação organizada por estruturas de classes e objetos e de troca de mensagens entre elas;
3) Comentários / Anotações:
   - Podem acrescentar informações para que o código seja compreender posteriormente pela desenvolvedora ou por outro membro ( /* ... */ );

## Tipos de Dados e Variáveis
  - <b>Núméricos:</b>
    - Inteiros --> int (-10, -1, 1, 10);
    - Real --> float (-1.50, 1.50);
    - Double --> intervalo menores de valores;
  - <b>Caracteres:</b>
    - Char --> char (' c ', ' * ', '   ');
  - <b>Lógico:</b>
    - Bool --> bool (true or false) - (#include <stdbool.h>);

  Indica uma lista de locais a serem reservados na memória. Para manipulá-los deve-se indicar um <b>Nome</b> para cada um deles e o <b>Tipo</b> que será utilizado como convenção / padrão para interpretação dos bits daquele local da memória.<br>
  <br>Como o conteúdo pode ser alterado várias vezes ao longo código, chama-se essa estrutura de armazenamento de variável. A declaração da variável é a nomeação e o tipo de cada lista. Por exemplo:
  - TIPO1 variavel1, variavel2, variavel3;
  - TIPON variavelN;

  Na declaração, cada variável é criada com um número aleatório chamado de "lixo". Por essa razão, é importante inicializar o seu conteúdo.<br> A inicialização pode ocorrer de várias formas:
  1) Na Declaração:
     - int x = 0; int y = 10;
     - Um igual (=) significa atribuição do conteúdo (ou resultado da expressão)
  2) No Meio do Código:
     - x = y + 5;
     - se uma variável é indicada do lado direito, o conteudo dela "naquela momento" é substituido para gerar o resultado da expressão antes de atribuí-lo. No exemplo, substitui 'y' por 10 e gerava em X o resultado 15, já o próprio 'y' não muda.
  3) Pelo Teclado:
     - scanf("%d %d", &x, &y);
     - o primeiro inteiro disponivel no (%d) "buffer"(área de armazenamento) de entrada padrão teclado é armazenado n primeiro endereço indicado, seguindo no segundo e assim por diante.

## Operadores e Expressões
1) Aritiméticos.
