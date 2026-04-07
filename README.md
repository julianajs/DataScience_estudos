🛠 Arquitetura e Engenharia de Prompt
Um diferencial deste projeto foi o uso de Prompt Engineering avançado para acelerar a entrega e garantir a robustez do código. O Gemini foi utilizado para:

Design de Pipeline: Estruturação lógica das etapas de ETL seguindo princípios de Clean Code.

Resolução de Conflitos: Tratamento resiliente de formatos de data/hora inconsistentes (detecção e correção de erros de parse).

Otimização de Algoritmos: Refinamento dos hiperparâmetros do modelo de Machine Learning e seleção de métricas de avaliação.


# ☕ Coffee Sales Intelligence: ETL, Viz & Forecasting

Este projeto de portfólio apresenta uma solução completa de análise de dados, desde a ingestão bruta até a predição de faturamento, utilizando um dataset de vendas de café do Kaggle.

## 🚀 Destaques Técnicos

### 1. ETL & Data Cleaning
- **Resiliência:** Tratamento de formatos de data/hora mistos (ISO8601 vs Padrão).
- **Feature Engineering:** Criação de variáveis sazonais e de períodos específicos (Early Morning, Lunch Peak, etc.).
- **Data Quality:** Limpeza de colunas de baixa variância e normalização de categorias.

### 2. Dashboard Interativo (Plotly)
- Análise de série temporal de faturamento.
- Treemap/Bar charts para análise de mix de produtos.
- Identificação visual de gargalos operacionais por horário.

### 3. Machine Learning
- **Modelo:** Random Forest Regressor.
- **Objetivo:** Prever o valor da transação com base em variáveis contextuais.
- **Métricas:** Alcance de um MAE (Mean Absolute Error) reduzido, demonstrando a estabilidade do modelo.

### 4. Utilização do Gemini

## 🛠 Stack Tecnológica
- **Linguagem:** Python 3.x
- **Manipulação:** Pandas, NumPy
- **Visualização:** Plotly (Interativo)
- **Machine Learning:** Scikit-Learn
