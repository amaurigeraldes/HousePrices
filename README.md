- Este repositório foi elaborado para explicar o Projeto do Kaggle: **HousePrices**
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/submissions

## Projeto de Ciência de Dados para Previsão de Valores de Imóveis

## Etapa 01: Primeiro Modelo
- Efetuamos nesta primeira fase tratamentos bastante simplistas nas Bases de Dados de Treino e de Teste, antes da aplicação dos Modelos, tais como:
  1) Exclusão de features com a porcentagem de valores nulos/vazios superior a 10%;
  2) Substituição dos valores nulos/vazios remanecente por -1;
  3) Exclusão das Colunas Não Numéricas;
 
- Aplicamos 3 Modelos/Algoritmos, a saber:
  Regressão Linear;
  Árvore de Decisão;
  KNeighborsRegressor;

- Utilizamos 2 Métodos para a Avaliação dos Modelos:
  Erro Médio Absoluto;
  Erro Quadrático Médio;

- Plotamos o Gráfico Comparativo para os 3 Modelos;

- Analisamos e concluimos nesta etapa que o melhor Modelo foi o da **Regressão Linear** por ter sido o algoritmo com menor erro quadrático médio, a mesma métrica utilizada pelo Kaggle para a classificação dos modelos.

- O resultado obtido e submentido ao Kaggle foi:
<img src="https://github.com/amaurigeraldes/HousePrices/blob/main/imagens/Resultado_Kaggle_HousePrices_01.jpg">


