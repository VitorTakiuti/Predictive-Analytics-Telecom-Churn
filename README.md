# Predictive-Analytics-Telecom-Churn
Predictive analysis and development of a Machine Learning model to forecast customer churn in a telecom company. Uses Python, Pandas, and Scikit-learn for data exploration and classification model training.

# Análise Preditiva de Churn de Clientes | Customer Churn Prediction

## 🇧🇷 Português

Este repositório contém uma análise completa e a construção de um modelo de Machine Learning para prever a evasão de clientes (churn) em uma empresa de telecomunicações. O projeto foi desenvolvido em um ambiente Google Colab, utilizando Python e suas principais bibliotecas de Data Science.

### O que foi feito?

O objetivo principal era identificar os fatores que mais contribuem para o cancelamento de serviços e criar um modelo preditivo capaz de classificar clientes como "propensos a evadir" ou "não propensos a evadir". Isso permite que a empresa atue de forma proativa para reter seus clientes.

### Como foi feito?

O projeto foi estruturado nas seguintes etapas:
1.  **Análise Exploratória de Dados (EDA):** Investigação inicial dos dados para identificar padrões, correlações entre variáveis e insights relevantes sobre o comportamento dos clientes.
2.  **Pré-processamento de Dados:** Limpeza dos dados, tratamento de valores ausentes e transformação de variáveis categóricas em formatos numéricos para preparar o dataset para a modelagem.
3.  **Treinamento de Modelos:** Foram treinados e comparados diferentes algoritmos de classificação (como Regressão Logística e Random Forest) para encontrar o que melhor se ajusta ao problema.
4.  **Avaliação de Performance:** O modelo final foi avaliado com base em métricas como Acurácia, Precisão e Recall para garantir sua eficácia na previsão de churn.

### Resultados Obtidos

O modelo final, baseado em **Random Forest**, alcançou uma **acurácia de 88%** na previsão de churn. Foi identificado que os principais fatores que levam ao cancelamento são o **tipo de contrato** (contratos mensais têm maior chance de churn) e o **valor da cobrança mensal**. O modelo pode ser utilizado para direcionar campanhas de retenção para clientes de alto risco.

------------------------------------------

## 🇺🇸 English

This repository contains a complete analysis and the development of a Machine Learning model to predict customer churn in a telecommunications company. The project was developed in a Google Colab environment, using Python and its main Data Science libraries.

### What Was Done?

The main goal was to identify the key factors contributing to service cancellation and to create a predictive model capable of classifying customers as "likely to churn" or "unlikely to churn." This enables the company to take proactive measures to retain its customers.

### How It Was Done?

The project was structured into the following steps:
1.  **Exploratory Data Analysis (EDA):** Initial investigation of the data to identify patterns, correlations between variables, and relevant insights into customer behavior.
2.  **Data Preprocessing:** Cleaning the data, handling missing values, and transforming categorical variables into numerical formats to prepare the dataset for modeling.
3.  **Model Training:** Different classification algorithms (such as Logistic Regression and Random Forest) were trained and compared to find the best fit for the problem.
4.  **Performance Evaluation:** The final model was evaluated based on metrics like Accuracy, Precision, and Recall to ensure its effectiveness in predicting churn.

### Results

The final model, based on **Random Forest**, achieved an **accuracy of 88%** in predicting churn. It was identified that the main drivers of cancellation are the **contract type** (monthly contracts have a higher churn rate) and the **monthly charges**. The model can be used to target retention campaigns at high-risk customers.
