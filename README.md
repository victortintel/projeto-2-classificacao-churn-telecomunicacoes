# Projeto de Classificação de Churn em Telecomunicações

## Descrição
Este projeto visa prever quais clientes de uma empresa de telecomunicações tem maior probabilidade de cancelar seus serviços (churn). O modelo desenvolvido permite à empresa direcionar esforços de retenção para os clientes de maior risco, otimizando recursos e aumentando a receita.

## Dataset
O dataset utilizado é o "Telco Customer Churn" disponível publicamente no Kaggle:
https://www.kaggle.com/blastchar/telco-customer-churn

Contém informações de 7.043 clientes com 21 atributos cada.

## Métricas Principais
- AUC-ROC: 0.85
- Precisão: 0.78
- Recall: 0.60
- F1-Score: 0.68

## Principais Insights
1. Clientes com contratos mensais tem 3x mais chance de churn
2. Valores mensais mais altos estão associados a maior risco
3. Serviços adicionais como suporte técnico reduzem o churn

## Como Executar
1. Clone o repositório
2. Instale as dependências: `pip install -r requirements.txt`
3. Execute o Jupyter Notebook: `jupyter notebook Churn_Analysis.ipynb`

## Dependências
- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- shap
