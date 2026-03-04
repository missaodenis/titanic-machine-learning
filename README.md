# Titanic - Machine Learning Project

Projeto desenvolvido com foco em prática de análise de dados, feature engineering e aplicação de algoritmos de Machine Learning utilizando o dataset da competição **Titanic - Machine Learning from Disaster (Kaggle)**.

---

## Objetivo

Prever quais passageiros sobreviveram ao desastre do Titanic.

---

## Etapas do Projeto

### Análise Exploratória

- Verificação de valores nulos
- Análise de tipos de dados
- Observação de padrões iniciais

### Limpeza de Dados

- Preenchimento de valores ausentes:
  - Age → mediana
  - Fare → mediana por classe
  - Embarked → moda
  - Cabin → categoria "Desconhecido"

### Feature Engineering

- Extração de título (Mr, Mrs, Miss, Master, Rare)
- Criação da variável Família (SibSp + Parch + 1)
- Agrupamento de Age em faixas
- Agrupamento de Fare em quartis
- Transformação de variáveis categóricas em numéricas

### Modelagem

Separação em:

- 80% treino
- 20% validação


Modelos testados:

- Logistic Regression
- Support Vector Machine
- KNN
- Naive Bayes
- Perceptron
- Linear SVC
- SGD Classifier
- Decision Tree
- Random Forest

---

## 📈 Resultados (Validação)

| Modelo | Accuracy |
|--------|----------|
| Decision Tree | ~83% |
| Random Forest | ~82% |
| SVC | ~82% |
| KNN | ~80% |
| Logistic Regression | ~79% |

---

## Principais Aprendizados

- Importância do Feature Engineering
- Separação correta entre treino e validação
- Diferença entre overfitting e generalização
- Comparação entre múltiplos algoritmos

---

## Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---