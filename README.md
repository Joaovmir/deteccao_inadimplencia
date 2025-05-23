# Detecção de Inadimplência em Empréstimos de Automóveis 🚗💸

[![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)

Este repositório apresenta uma análise de dados e um pipeline de ciência de dados para a **detecção e previsão de inadimplência em empréstimos de automóveis**. Utiliza técnicas de aprendizado de máquina para identificar clientes com maior risco de inadimplência, apoiar decisões de crédito e melhorar a saúde financeira da carteira de empréstimos.

---

## 🌟 Motivação

A inadimplência em financiamentos de veículos representa um dos principais riscos para instituições financeiras. Antecipar e identificar clientes propensos ao não pagamento permite implementar políticas preventivas, ajustar taxas, ofertar renegociações e proteger a sustentabilidade do negócio.

---

## 🎯 Objetivos do Projeto

- Explorar e analisar o perfil dos clientes e contratos de empréstimo de automóveis.
- Identificar variáveis preditoras relevantes para inadimplência.
- Construir, treinar e avaliar modelos de classificação para previsão de risco.
- Visualizar resultados e métricas de desempenho dos modelos.
- Disponibilizar um **notebook interativo** para replicação, experimentação e aprimoramento do pipeline.

---

## 🗂️ Etapas do Projeto

1. **Carregamento dos dados** (`emp_automovel.csv`)
2. **Limpeza e pré-processamento** (tratamento de valores ausentes, encoding, normalização)
3. **Análise exploratória de dados** (visualizações, estatísticas, correlações)
4. **Treinamento e validação de modelos de classificação** (ex: Random Forest, Logistic Regression, XGBoost)
5. **Avaliação de métricas** (Acurácia, ROC-AUC, matriz de confusão, precisão, recall)
6. **Discussão dos resultados** e sugestões para aplicações reais

---

## 📚 Tecnologias Utilizadas

- [Python 3.8+](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

---

## ⚡ Como Rodar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/Joaovmir/deteccao_inadimplencia.git
cd deteccao_inadimplencia
````

### 2. Instale as dependências

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
# Adicione xgboost se usado
```

### 3. Estrutura dos Dados

A pasta `dados/` deve conter:

* `emp_automovel.csv`
  Base de dados de clientes, contratos e status de inadimplência.

### 4. Execute o notebook

Abra e execute o arquivo `deteccao_inadimplencia.ipynb` em seu ambiente Jupyter, VS Code ou Colab.

---

## 📁 Estrutura do Projeto

```
deteccao_inadimplencia/
├── deteccao_inadimplencia.ipynb
├── dados/
│   └── emp_automovel.csv
├── README.md
```

---

## 🔎 Possíveis Expansões

* Testar diferentes algoritmos (XGBoost, LightGBM, SVM, redes neurais).
* Otimização de hiperparâmetros e validação cruzada.
* Balanceamento de classes (SMOTE, under/oversampling).
* Deploy do modelo em uma API para scoring em produção.
