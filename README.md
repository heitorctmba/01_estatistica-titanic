# Titanic — Análise Estatística de Sobrevivência

Projeto da disciplina de **Estatística Descritiva** do MBA em Ciência de Dados.

## Objetivo

Analisar o perfil dos passageiros do Titanic e identificar padrões de sobrevivência associados à classe, sexo e faixa etária, com foco em distribuição de tarifas e desigualdades demográficas.

## Dados

| Arquivo | Fonte | Descrição |
|---|---|---|
| `titanic.csv` | Professor | Dataset principal: passageiros, tarifas e resultado de sobrevivência |

## Estrutura do Notebook

1. **Imports**
2. **Carregamento e Preparação** — carregamento do dataset e criação da variável de faixa etária
3. **Análise Exploratória** — distribuição de tarifas, análise por classe e variáveis qualitativas (sexo, classe, faixa etária)
4. **Síntese e Conclusões** — tabelas descritivas e padrões identificados

## Principais Achados

- Passageiros de 1ª classe tiveram taxa de sobrevivência de **62,9%**, contra **24,2%** na 3ª classe
- Mulheres sobreviveram a uma taxa de **74,2%**, frente a **18,9%** dos homens
- Sobreviventes pagaram tarifa média **2,2x maior** que a dos não sobreviventes

## Requisitos

```
pandas
matplotlib
scipy
numpy
```
