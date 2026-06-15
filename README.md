# Detecção de Fraudes Bancárias com Machine Learning

Projeto desenvolvido como parte de um desafio prático de Machine Learning.

O objetivo é construir modelos capazes de identificar transações fraudulentas em operações bancárias utilizando técnicas de classificação supervisionada.

---

## Objetivo

Desenvolver e comparar modelos de Machine Learning para detecção de fraudes financeiras, avaliando desempenho e interpretabilidade.

---

## Dataset

O projeto utiliza o conjunto de dados Credit Card Fraud Detection Dataset.

Características:

- Transações realizadas por cartões de crédito
- Classes altamente desbalanceadas
- Variável alvo:
  - 0 = Transação legítima
  - 1 = Fraude

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- SHAP

---

## Etapas do Projeto

### 1. Análise Exploratória

- Verificação da estrutura dos dados
- Identificação de valores ausentes
- Avaliação do desbalanceamento das classes

### 2. Pré-processamento

- Separação de variáveis preditoras e alvo
- Escalonamento dos dados
- Divisão treino e teste

### 3. Modelagem

Foram avaliados os seguintes modelos:

- Regressão Logística
- Random Forest
- XGBoost

### 4. Avaliação

Métricas utilizadas:

- Precision
- Recall

![Relação Precision Recall](images/precision recall.png)

- F1-Score
- ROC-AUC
- Matriz de Confusão

### 5. Interpretabilidade

Aplicação de SHAP para compreensão da influência das variáveis nas previsões.

---

## Estrutura do Projeto

```text
Detecção de fraudes bancárias/
│
├── docs em py/
      └── Desafio em python com comentários
      └── Desafio em python sem comentários
├── images/
├── notebooks/
     └── Notebook (colab) com comentários
     └── Notebook (colab) sem comentários
├── .gitignore 
├── README.md
└── requirements.txt
```


## Principais Resultados

- Comparação entre diferentes algoritmos
- Avaliação de desempenho em cenário de classes desbalanceadas
- Interpretação das previsões utilizando SHAP
