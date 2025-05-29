# 🩺 Previsão de Câncer de Próstata - Competição Novembro Azul

Este projeto foi desenvolvido como parte da competição **"Prostate Cancer (Novembro Azul)"**, que tem como objetivo prever a probabilidade de um paciente ter câncer de próstata com base em características clínicas extraídas de exames.

## 🧠 Sobre a Competição

A tarefa consiste em criar um modelo de classificação que consiga prever com precisão se um paciente tem câncer de próstata.  
O conjunto de dados contém 9 variáveis principais, incluindo:

- Radius  
- Texture  
- Perimeter  
- Area  
- Smoothness  
- Compactness  
- Symmetry  
- Fractal dimension  
- Diagnosis result (variável alvo)

Essas variáveis são extraídas de exames clínicos e refletem propriedades morfológicas da próstata.

## ✅ O que foi feito

### 1. Análise e Exploração de Dados
- Verificação da proporção dos dados
- Análise da distribuição das variáveis
- Visualização de dados para melhor entendimento do comportamento das variáveis

### 2. Processamento de Dados
- Aplicação de técnicas de escalonamento (scaling)
- Divisão dos dados em conjunto de treino e teste

### 3. Construção e Comparação de Modelos de Classificação
Modelos utilizados:
- Random Forest Classification  
- Decision Tree Classification  
- KNN Classification  
- Logistic Regression Classification

Para comparar o desempenho dos modelos, foram utilizadas as métricas de **acurácia** e **matriz de confusão**.

## 🏆 Resultados

O modelo com melhor desempenho foi a **Decision Tree Classification**, atingindo uma **acurácia de 86,67%**.  
Apesar disso, os outros modelos também apresentaram resultados satisfatórios, com destaque para o **Random Forest**.

## 📂 Fonte dos Dados

🔗 Dataset utilizado neste projeto: [Kaggle - Prostate Cancer Dataset](https://www.kaggle.com/datasets/sajidsaifi/prostate-cancer)
