# Credit Card Fraud Detection and Prevention
Analisando padrões de fraude em transações com cartões de crédito e explorando métodos de detecção e prevenção.

## Descrição do Projeto
Este projeto visa analisar padrões de fraude em cartões de crédito, entender os fatores que contribuem para atividades fraudulentas e explorar métodos eficazes de detecção e prevenção. Utilizando um conjunto de dados simulado de transações, o objetivo é desenvolver modelos preditivos que possam identificar transações fraudulentas com base em características como valor da transação, tipo de transação, e localização.

A análise busca fornecer insights sobre as causas e os métodos de prevenção da fraude, utilizando aprendizado de máquina para identificar transações suspeitas.

## Sobre o Dataset
O dataset simula 100.000 transações realizadas com cartões de crédito. Ele contém as seguintes características:

- TransactionID: Identificador único para cada transação.
- TransactionDate: Data e hora da transação.
- Amount: Valor da transação, útil para identificar transações de valor inusitado que podem indicar fraude.
- MerchantID: Identificador do comerciante envolvido, importante para analisar fraudes relacionadas ao comerciante.
- TransactionType: Tipo de transação (compra ou reembolso), que ajuda a contextualizar a atividade.
- Location: Localização geográfica da transação, facilitando a análise de fraudes por região.
- IsFraud: Variável binária que indica se a transação foi fraudulenta (1 para fraude, 0 para legítima).

## Objetivos da Análise
1) Análise Exploratória de Dados (EDA):
- Examinar a distribuição dos valores e tipos de transações.
- Identificar tendências nas datas e localizações das transações.
- Analisar a proporção de transações fraudulentas em relação às legítimas.
  
2) Reconhecimento de Padrões:
- Utilizar técnicas de clustering para agrupar transações e identificar padrões atípicos.
- Explorar correlações entre as características das transações e a ocorrência de fraudes.
  
3)  Modelagem de Detecção de Fraudes:
- Implementar algoritmos de aprendizado de máquina, como regressão logística, árvores de decisão e florestas aleatórias, para construir modelos preditivos.
- Avaliar o desempenho dos modelos usando métricas como acurácia, precisão, recall e F1 score.

4) Análise de Importância das Features:
- Identificar as características mais importantes para a detecção de fraudes, aprimorando os sistemas de detecção de fraudes.

### Fonte:
Dataset no Kaggle: [https://www.kaggle.com/api/v1/datasets/download/mlg-ulb/creditcardfraud](https://www.kaggle.com/api/v1/datasets/download/bhadramohit/credit-card-fraud-detection)

## Tecnologias Utilizadas
Linguagem: Python

Bibliotecas:
- Manipulação de dados: Pandas, NumPy
- Visualização: Matplotlib, Seaborn, Plotly
- Modelagem: 
- Avaliação: 
