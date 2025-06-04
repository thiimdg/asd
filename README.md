# Projeto de Predição de Preços de Imóveis em Madrid

Este projeto tem como objetivo desenvolver um modelo de machine learning para prever os preços de imóveis em Madrid com base nas características coletadas no dataset.

## Sobre o Projeto

Objetivo: Criar um modelo preditivo para estimar o valor de imóveis em Madrid.

Modelos Utilizados: Regressão Linear e Random Forest.

Resultados: O Random Forest obteve um melhor desempenho geral como modelo para esse caso.

## Como Usar

1) Instale os Requerimentos

```bash
pip install -r requirements.txt
```

Para abrir o notbook diretamente no Google Colab clique no botão "Open in Colab".

Faça o upload do dataset quando solicitado.

## Estrutura do Projeto

```
├── houses_Madrid.csv              # Dataset utilizado
├── MadridRealState.ipynb  # Notbook
├── README.md              # Este arquivo
└── requirements.txt       # Dependências
```

## Principais Resultados
Modelo -	           MAE (€) -	RMSE (€) -	R² Score

Regressão Linear -	 147.163 -	220.770 -	  0.576

Random Forest	 -    135.460	- 209.366 -	  0.667

## Próximos Passos

Feature Engineering: Criar novas variáveis para utilização.

Testar outros modelos: Gradient Boosting (XGBoost, LightGBM) por exemplo.
