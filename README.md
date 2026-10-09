# Classificação de Diabetes com KNN e Random Forest

Trabalho parcial da disciplina Ciência de Dados e Inteligência Artificial.

**Autora:** Nayra Naara Gomes Macario

## Objetivo
Realizar análise exploratória e comparar os modelos KNN e Random Forest na classificação do alvo Diabetes, criado a partir de glyhb ≥ 6,5.

## Dataset
Dataset disponível no Kaggle: https://www.kaggle.com/datasets/imtkaggleteam/diabetes

## Metodologia
- Análise exploratória dos dados.
- Divisão em 60% treino, 20% validação e 20% teste.
- Preenchimento dos valores ausentes usando somente o treino como referência.
- Cálculo do IMC e seleção de variáveis.
- Escolha das configurações na validação, sem Pipeline.
- Avaliação no teste e salvamento dos modelos com joblib.

## Resultados no teste
| Modelo | Acurácia | Acurácia balanceada |
|---|---:|---:|
| KNN | 88,46% | 74,62% |
| Random Forest | 91,03% | 79,23% |

## Execução
Abra o arquivo .ipynb no Google Colab e execute as células na ordem.

## Limitações
A análise exploratória utilizou o dataset completo, e o teste foi consultado em tentativas anteriores. Os resultados devem ser interpretados considerando essa limitação.
