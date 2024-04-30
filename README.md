# Análise Exploratória de Dados
Durante a análise exploratória, identificamos algumas tendências importantes:

Tipo de Viagem: O tipo de viagem mais comum é o roundtrip, indicando uma preferência por viagens de ida e volta, principalmente para períodos de férias.
Canal de Vendas: A maioria das passagens é vendida online, sugerindo uma forte presença de vendas por meio da internet.
Dia da Semana com Mais Voos: Segunda-feira é o dia com o maior número de voos, refletindo uma alta atividade de viagens no início da semana.
Dia da Semana com Menos Voos: Sábado registra o menor número de voos, indicando uma menor atividade de viagens durante o fim de semana.
Rotas Mais Procuradas: As rotas mais procuradas são aquelas envolvendo "AKLKUL", sugerindo alta demanda por esse trajeto específico.
País com Mais Reservas de Viagem: A Austrália é o país com o maior número de reservas de viagem, destacando-se como um destino popular entre os viajantes.

# Previsão de Demanda de Passageiros
Para prever a demanda de passageiros com base nos dados disponíveis, foram utilizados diferentes modelos de aprendizado de máquina:

Random Forest:
Utilizando o algoritmo Random Forest, alcançamos um Mean Absolute Error (MAE) de aproximadamente 0.661, fornecendo uma estimativa inicial da precisão do modelo.
XGBoost:
O modelo XGBoost apresentou um desempenho ligeiramente melhor, com um MAE de cerca de 0.636, indicando uma melhoria na capacidade de previsão em comparação com o Random Forest.
Rede Neural:
Além dos modelos baseados em árvores, uma rede neural simples foi treinada e avaliada. O modelo de rede neural obteve um MAE de aproximadamente 0.636, mostrando uma eficácia semelhante aos modelos de conjunto.
Expectativas da Previsão
Com base nos resultados obtidos, esperamos que os modelos treinados possam oferecer previsões precisas da demanda de passageiros com base nos atributos fornecidos.
