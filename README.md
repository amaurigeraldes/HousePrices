- Este repositório foi elaborado para explicar o Projeto do Kaggle: **HousePrices**
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/submissions

# Projeto Ciência de Dados: Prever Valores de Imóveis

- O arquivo utilizado para o desenvolvimento está disponível neste mesmo repositório através do Link:
https://github.com/amaurigeraldes/HousePrices/blob/main/Projeto_House_Prices_Dataset_Kaggle_v01.ipynb

## Etapa 01: Primeiro Modelo
- Efetuamos nesta primeira fase tratamentos bastante simplistas nas Bases de Dados de Treino e de Teste, antes da aplicação dos Modelos, tais como:
  1) Exclusão de features com a porcentagem de valores nulos/vazios superior a 10%;
  2) Substituição dos valores nulos/vazios remanecente por -1;
  3) Exclusão das Colunas Não Numéricas;
 
- Aplicamos 3 Modelos/Algoritmos, a saber:
    - Regressão Linear;
    - Árvore de Decisão;
    - KNeighborsRegressor;

- Utilizamos 2 Métodos para a Avaliação dos Modelos:
    - Erro Médio Absoluto;
    - Erro Quadrático Médio;

- Plotamos o Gráfico Comparativo para os 3 Modelos:
<img src="https://github.com/amaurigeraldes/HousePrices/blob/main/imagens/graficos_modelos_previsao.png">

- Analisamos e concluimos que nesta etapa o melhor Modelo foi o da **Regressão Linear** por ter sido o algoritmo com menor erro quadrático médio, a mesma métrica utilizada pelo Kaggle para a classificação dos modelos.


- O resultado obtido e submetido ao Kaggle foi:
<img src="https://github.com/amaurigeraldes/HousePrices/blob/main/imagens/Resultado_Kaggle_HousePrices_01.jpg">


