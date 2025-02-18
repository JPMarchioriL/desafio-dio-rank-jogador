# Calculadora de Partidas Rankeadas

Este repositório contém uma calculadora que determina o nível de um jogador em um jogo de rankeadas com base nas suas vitórias e derrotas.

## Como funciona

A função `nivelRankeadas` recebe como parâmetros a quantidade de vitórias e derrotas de um jogador, calcula o saldo de vitórias (vitórias - derrotas), e, com base nesse saldo, determina o nível do jogador de acordo com os seguintes critérios:

- Se vitórias for menor que 10: **Ferro**
- Se vitórias estiver entre 11 e 20: **Bronze**
- Se vitórias estiver entre 21 e 50: **Prata**
- Se vitórias estiver entre 51 e 80: **Ouro**
- Se vitórias estiver entre 81 e 90: **Diamante**
- Se vitórias estiver entre 91 e 100: **Lendário**
- Se vitórias for maior ou igual a 101: **Imortal**
