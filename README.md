# Simulador BCD + 7447 + Display 7 Segmentos

Simulador interativo que demonstra o funcionamento de um circuito decodificador **BCD 8421 → CI 7447 → Display de 7 Segmentos**, desenvolvido como apoio para aulas de Sistemas Eletrônicos Digitais.

## Objetivo

Permitir que estudantes visualizem, antes de irem para a bancada, todo o caminho de um sinal digital desde a representação decimal até a exibição no display de 7 segmentos.

## Funcionamento

A interface é dividida em três painéis que representam os blocos do circuito real:

**1. Entrada Decimal e Codificação BCD** — Botões de 0 a 15 e quatro switches (A, B, C, D) com pesos 1, 2, 4 e 8. Ao clicar em um número, os switches se ajustam automaticamente; ao mover os switches, o valor decimal é calculado em tempo real.

**2. Decodificador CI 7447** — Mostra a pinagem do CI com as entradas BCD e as saídas para cada segmento (a-g) em lógica ativo-baixo, refletindo o comportamento real do componente com display de Ânodo Comum.

**3. Display de 7 Segmentos** — Display estilizado que acende dinamicamente conforme o valor de entrada, reproduzindo inclusive os caracteres "estranhos" gerados por entradas inválidas (10 a 15), conforme datasheet do CI.

## Como executar

Abra o arquivo `index.html` no navegador. Sem dependências externas.
