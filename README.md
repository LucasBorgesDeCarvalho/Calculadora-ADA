﻿# Calculadora-ADA
 
Este projeto implementa uma calculadora básica em HTML, CSS e TypeScript. A calculadora possui as funcionalidades de adição, subtração, multiplicação, divisão, e o botão de limpar, além de um design responsivo para diferentes tamanhos de tela.

## Funcionalidades

- **Entrada de Números**: Você pode inserir números clicando nos botões da calculadora.
- **Operações Matemáticas**: Suporta as operações de adição (`+`), subtração (`-`), multiplicação (`*`), e divisão (`/`).
- **Cálculo**: Pressione o botão `=` para calcular o resultado da operação.
- **Limpar**: O botão `C` limpa o display e reseta a calculadora.
- **Decimais**: Suporta a entrada de números decimais.

## Estrutura do Projeto

### Arquivos

- `index.html`: Contém a estrutura HTML da calculadora.
- `styles.css`: Contém o estilo visual da calculadora, incluindo layout e cores.
- `script.js`: Contém a lógica da calculadora em TypeScript/JavaScript.

### Classes e Funções

- **`Calculator`**: Classe que gerencia o estado da calculadora (valores atuais, operações, e o display).
  - **`appendNumber(number: string)`**: Adiciona números ao display, evitando múltiplos pontos decimais.
  - **`chooseOperation(operation: string)`**: Define a operação matemática atual.
  - **`compute()`**: Realiza o cálculo baseado nos valores e operação selecionada.
  - **`clear()`**: Reseta os valores e o display.
  - **`updateDisplay()`**: Atualiza o display com o valor atual.

### Estilo

A calculadora tem um design moderno, com um fundo escuro e botões com cores diferenciadas para operações e ações principais. A interface é responsiva, adaptando-se a diferentes resoluções de tela.

### Comportamento Responsivo

- O layout e o tamanho dos botões são ajustados para telas menores, garantindo uma experiência consistente em dispositivos móveis.

## Como Executar

1. Clone este repositório.
2. Abra o arquivo `index.html` em um navegador da web.

## Personalizações Futuras

- Implementar mais operações matemáticas como potenciação ou raiz quadrada.
- Adicionar suporte para teclas do teclado para facilitar a entrada de dados.
