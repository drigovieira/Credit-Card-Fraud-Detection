# Credit Card Fraud Detection
## Identificação de transações fraudulentas com base em aprendizado de máquina.

### Descrição do Projeto
Este projeto utiliza aprendizado de máquina para identificar fraudes em transações com cartão de crédito. O foco principal é lidar com a desbalanceamento de classes, já que apenas 0,172% das transações são fraudulentas. As técnicas empregadas incluem análise exploratória de dados, seleção de variáveis, engenharia de features e treinamento de modelos preditivos.

O objetivo é criar um modelo robusto que maximize a métrica AUC-PR (Área sob a Curva de Precisão e Recall), já que métricas como acurácia são ineficazes para datasets altamente desbalanceados.

### Sobre o Dataset
O dataset contém transações realizadas por cartões de crédito em setembro de 2013 por clientes europeus.

### Características principais:
Tamanho: 284.807 transações, sendo 492 fraudulentas.
###Variáveis:
Time: Segundos decorridos desde a primeira transação.
Amount: Valor da transação.
V1 a V28: Componentes principais derivados de uma transformação PCA.
Class: Rótulo da transação (1 para fraude, 0 caso contrário).
