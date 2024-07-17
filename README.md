# Artificial Intelligence Scripts

Repositório de scripts de inteligência artificial, que vão desde a comparação de modelos, a implementação da metodologia CRISP-DM e noções de inteligência artificial responsável.

## CRISP-DM

<p align="center">
  <img alt="RFECV" src="./crisp-dm/assets/rfecv.png" style="width:49%">
  <img alt="Algorithms comparison" src="./crisp-dm/assets/comparison.png" style="width:49%">
</p>

Implementa a metodologia CRISP-DM para prever se existe um movimento de bando de __boids__. O projeto é ótimo para seleção de features e comparação estatística de modelos. Os seguintes classificadores foram comparados:
1. SVM (Support Vector Machine)
2. MLP (Multi-layer Perceptron)
3. Random Forest
4. LVQ (Learning Vector Quantization)
5. Comitê heterogêneo (Voting Classifier de Decision Tree, SVM e KNN)
6. Comitê homogêneo (MLPs)
7. Entre outros...

## Responsible AI

<p align="center">
  <img alt="PDP in 2D" src="./responsible-ai/pdp_knn.png">
</p>

Explica Explainable AI na prática, detalhando o que é, os seus métodos e como implementá-los a partir dos dados sobre ataques cardíacos. Os seguintes métodos foram implementados:
1. Global Surrogate
2. Feature Importance
3. Partial Dependence Plot
4. Individual Conditional Expectation
5. Local Surrogate

## Wine Analysis

![Wine feature tree](./wine-analysis/wine-tree.svg)

Análise de um dataset de vinhos, com o objetivo de prever o tipo de vinho baseado em suas característica, no qual é realiza a comparação dos seguintes classificadores:
1. Arvores de decisão
2. Bayesiano ingenuo
3. Regressão logística
4. K-vizinhos
