# DESAFIO_SUPERTRUNFOC 🃏

Este projeto é parte do desafio de programação em C para o jogo **Super Trunfo**, desenvolvido por Wallace Reis. O objetivo é comparar cartas de cidades brasileiras com base em atributos como população, área, PIB e outros indicadores.

## 📌 Descrição

O programa permite comparar duas cartas pré-definidas com base em atributos numéricos. O jogador pode escolher os atributos via menu interativo, e o sistema determina a carta vencedora com base nas regras específicas de cada atributo.

## 🧠 Funcionalidades

- Cadastro de cartas com os seguintes atributos:
  - Estado
  - Código
  - Nome da cidade
  - População
  - Área
  - PIB
  - Pontos turísticos
  - Densidade populacional (calculada)
  - PIB per capita (calculado)

- Menu interativo para escolha de atributos
- Comparação entre dois atributos diferentes
- Regras específicas:
  - Maior valor vence (exceto densidade populacional)
  - Menor densidade populacional vence
- Tratamento de empate
- Exibição clara dos resultados

## ⚙️ Como compilar e executar

### Requisitos:
- Compilador GCC instalado
- Terminal ou VS Code com suporte a C

### Passos:

```bash
gcc desafio_supertrunfo.c -o supertrunfo
./supertrunfo 



Escolha o primeiro atributo para comparação:
1 - População
2 - Área
3 - PIB
...

Escolha o segundo atributo (diferente do primeiro):
...

=== Resultado da Comparação ===
Atributo 1: População
Carta 1: 220444
Carta 2: 241835

Atributo 2: PIB
Carta 1: 3.20
Carta 2: 6.10

Pontuação Final:
Carta 1: 0 ponto(s)
Carta 2: 2 ponto(s)

🏆 Carta 2 (Sete Lagoas) venceu!
Wallace Reis
Santa Luzia - MG



