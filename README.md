# MVP_ML_Analytics_PMAR

MVP da Sprint de Machine Learning & Analytics  
Autor: Pedro Mendes de Azambuja Rodrigues  
Data: 26/09/2025  

## Descrição
O objetivo deste projeto é desenvolver modelos de classificação binária para prever readmissões hospitalares em até 30 dias após a alta, utilizando o dataset público [Diabetes 130-US hospitals (1999–2008)](https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008).

## Estrutura do repositório
- `MVP_ML_PMAR_final_.ipynb` → notebook principal com análise, modelagem e avaliação.  
- `data/` → dados utilizados.  
- `models/` → pipeline CatBoost salvo em `.pkl`.  
- `README.md` → este arquivo.  

## Execução
1. Abra o notebook no Google Colab:  
   [Abrir no Colab](https://colab.research.google.com/github/pedro-aza/MVP_ML_Analytics_PMAR/blob/main/MVP_ML_PMAR_final_.ipynb)  

2. Execute todas as células em ordem (Runtime > Run all).  

3. O controle de execução está definido como LOAD_PRETRAINED = True para carregar o pipeline já treinado salvo em `models/` e executar o notebook. Se desejar reproduzir o RandomizedSearchCV completo ajuste LOAD_PRETRAINED para False e rode novamente. 

## Observações
- O notebook já parte de uma versão limpa do dataset (remoção de variáveis com muitos faltantes, exclusão de óbitos/cuidados paliativos, agrupamento de categorias raras). 


