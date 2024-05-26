# Previsão de Cancelamento de Reserva em Hotéis com Redução de Dimensionalidade
![Static Badge](https://img.shields.io/badge/Status-Finalizado-green)

## Descrição

Este projeto explora o impacto da redução de dimensionalidade na performance de um modelo de Machine Learning para prever o cancelamento de reservas em hotéis. Através da aplicação de diferentes técnicas de seleção de features, o projeto visa construir um modelo robusto e eficiente para classificar as reservas como canceladas ou confirmadas.

## Tecnologias Utilizadas

* **Linguagem de Programação:** Python
* **Bibliotecas:** Pandas, NumPy, Scikit-learn, Matplotlib, Plotly
* **Algoritmo de Machine Learning:** Random Forest Classifier

## Descrição Detalhada

Este projeto foi desenvolvido como parte do curso de Machine Learning da Alura, com o objetivo de aplicar e avaliar diferentes técnicas de redução de dimensionalidade. O dataset utilizado contém informações sobre reservas de hotel, sendo a variável alvo a situação da reserva (cancelada ou não).

**Etapas do Projeto:**

1. **Análise Exploratória de Dados:** 
    * Verificação e tratamento de dados nulos.
    * Análise do balanceamento da variável alvo.
    * Visualização de dados através de gráficos para identificar padrões e relações entre as features.
    * Análise de correlação entre as variáveis.

2. **Modelagem e Redução de Dimensionalidade:**
    * Criação de um modelo baseline utilizando todas as features com o algoritmo Random Forest Classifier.
    * Aplicação de técnicas de seleção de features para reduzir a dimensionalidade do dataset:
        * Feature Importances do modelo baseline.
        * SelectFromModel com e sem validação cruzada.
        * Recursive Feature Elimination (RFE) com e sem validação cruzada.

3. **Avaliação de Performance:**
    * Comparação da performance dos modelos treinados com diferentes conjuntos de features após a redução de dimensionalidade.
    * Métricas de avaliação: Acurácia, Precisão, Recall, F1-Score, AUC.

**Resultados Esperados:**

* Identificar as features mais relevantes para a previsão de cancelamento de reservas.
* Avaliar o impacto da redução de dimensionalidade na performance do modelo.
* Selecionar o melhor conjunto de features e técnica de redução de dimensionalidade para o problema em questão.

**Observações:**

* Este projeto serve como um guia prático para a aplicação de técnicas de redução de dimensionalidade em um problema de classificação.
