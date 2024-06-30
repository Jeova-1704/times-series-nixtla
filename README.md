# NIXTLA:
A Nixtla é composta por uma coleção de bibliotecas de código aberto, projetadas para fornecer um conjunto abrangente e avançado de ferramentas para previsão de séries temporais. O ecossistema Nixtla é construído principalmente em torno de cinco bibliotecas principais, cada uma especializada em diferentes aspectos da previsão de séries temporais:
### Bibliotecas Principais
- MLForecast(Quer foi o utilizado para esse projeto): Esta biblioteca torna o aprendizado de máquina escalável para previsão de séries temporais. É especialmente adequada para aplicações que exigem o processamento de grandes quantidades de dados de séries temporais, implementando técnicas de aprendizado de máquina para otimizar precisão, eficiência e escalabilidade.

- StatsForecast: Focada em métodos estatísticos para previsão de séries temporais. Ela oferece uma ampla gama de modelos tradicionais, como ARIMA, ETS, e outros modelos baseados em estatísticas.

- ForecastingBase: Proporciona uma base para a construção de modelos de previsão personalizados, permitindo a implementação de modelos específicos e técnicas avançadas de previsão.

- NeuralForecast: Integra técnicas de aprendizado profundo (deep learning) para previsão de séries temporais, fornecendo ferramentas para a construção e treinamento de redes neurais complexas para tarefas de previsão.

- TemporalHierarchy: Especializada em previsões de séries temporais hierárquicas, onde os dados são estruturados em diferentes níveis hierárquicos e as previsões precisam ser feitas considerando essas hierarquias.

## Modelos de Machine Learning (sklearn)
### Modelos
- LinearRegression: Um modelo linear que assume uma relação linear entre as variáveis independentes e a variável dependente.
- MLPRegressor: Um regressor de rede neural que utiliza múltiplas camadas de perceptrons.
- KNeighborsRegressor: Um modelo baseado no algoritmo k-Nearest Neighbors, que utiliza a proximidade dos dados de treinamento para fazer previsões.
- XGBRegressor: Um modelo de árvore de decisão baseado em gradient boosting, altamente eficiente e utilizado para tarefas de previsão complexas.
### Métricas
- MAPE (Mean Absolute Percentage Error): Mede a precisão de um modelo de previsão, calculando a média dos erros percentuais absolutos entre os valores previstos e os reais.
- MSE (Mean Squared Error): Mede a precisão de um modelo de previsão, calculando a média dos quadrados dos erros entre os valores previstos e os reais.
- RMSE (Root Mean Squared Error): A raiz quadrada do MSE, fornecendo uma medida da diferença entre os valores previstos e os reais.

## Séries Temporais
Séries temporais são conjuntos de dados ordenados no tempo. Elas são frequentemente utilizadas em previsões porque as observações passadas podem conter informações valiosas sobre o comportamento futuro da série. Exemplos comuns incluem dados financeiros, dados meteorológicos e dados de produção industrial.
