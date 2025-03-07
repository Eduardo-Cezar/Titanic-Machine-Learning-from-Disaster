# Titanic - Machine Learning from Disaster

Este repositório contém um notebook Python desenvolvido para a competição do Kaggle [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic). O objetivo da competição é prever quais passageiros sobreviveram ao naufrágio do Titanic com base em dados fornecidos, como classe social, sexo, idade, porto de embarque, entre outras informações.

## Descrição do Projeto

O notebook implementa várias técnicas de machine learning para prever a sobrevivência dos passageiros. O código original foi modificado e aprimorado para melhorar a acurácia do modelo. As principais abordagens utilizadas incluem:

- **Ajuste de hiperparâmetros** utilizando a função `gp_minimize` para otimizar os modelos.
- **Seleção de features** com base em uma matriz de correlação para identificar as variáveis mais relevantes.
- **Modelos de machine learning** como Regressão Logística, KNN, Naive Bayes, SVM, Árvores de Decisão e Random Forest.
- **Modelo ensemble** que combina os resultados de vários algoritmos para melhorar a previsão.

## Estrutura do Código

O notebook está organizado da seguinte forma:

1. **Introdução**: Apresentação do problema e dos dados.
2. **Metodologia**: Descrição das técnicas utilizadas e das modificações realizadas no código original.
3. **Implementação**:
   - Ajuste de hiperparâmetros para SVC, KNN, Naive Bayes e Regressão Logística.
   - Seleção de features com base na matriz de correlação.
   - Utilização de `get_dummies` para transformar variáveis categóricas em colunas booleanas.
4. **Resultados**: Discussão dos resultados obtidos com as diferentes abordagens.
5. **Conclusão**: Análise final sobre o desempenho do modelo e possíveis melhorias.

## Resultados

As principais conclusões do projeto são:

- O ajuste fino de hiperparâmetros utilizando `gp_minimize` resultou em uma melhoria na acurácia do modelo.
- A seleção de features e o uso de `get_dummies` não trouxeram os resultados esperados, reduzindo a acurácia do modelo.
- O problema possui uma complexidade inerente devido à aleatoriedade dos eventos, o que dificulta a obtenção de uma acurácia próxima de 100% sem overfitting.