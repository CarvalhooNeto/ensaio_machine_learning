# Contexto

A empresa Data Money fornece serviços de consultoria de Análise e Ciência de Dados para grandes
empresas no Brasil e no exterior.
O seu principal diferencial de mercado em relação aos concorrentes é o alto retorno financeiro para as
empresas clientes, graças a performance de seus algoritmos de Machine Learning.
A Data Money acredita que a expertise no treinamento e ajuste fino dos algoritmos, feito pelos Cientistas de
Dados da empresa, é a principal motivo dos ótimos resultados que as consultorias vem entregando aos seus
clientes.
Para continuar crescendo a expertise do time, os Cientistas de Dados acreditam que é extremamente
importante realizar ensaios nos algoritmos de Machine Learning para adquirir uma experiência cada vez
maior sobre o seu funcionamento e em quais cenários as performances são máximas e mínimas, para que a
escolha do algoritmo para cada situação seja a mais correta possível.
Como Cientista de Dados recém contratado pela empresa, a sua principal tarefa será realizar 3 ensaios com
algoritmos de Classificação, Regressão e Clusterização, a fim de extrair aprendizados sobre o seu
funcionamento em determinados cenário e conseguir transmitir esse conhecimento para o restante do time.


# Metodologia

Neste ensaio foram utilizados 16 algoritmos de machine learning dividios em classificação, regressão e 
clusterização. Dentre o treinamento desses algoritmos foram empregnados técnincas de seleção de features, 
validação houldout, teste sobres os datasets de treino, ROC curve,  validação e teste e visualização de dados através
de gráficos e tabelas.
Para os algoritmos de classificação foram adotados as métricas de avaliação como sendo: Acurácia, precisão, recall e
F1 score. Para os algoritmos de regressão foram utilzados as métrica de R2, MSE, RMSE, MAE e MAPE. Já para os algoritmos
de clusterização foi utilizada a silhuette score.

# Resultados

Apesar de ter utilizado testes sobre os diferentes datasets, considerei como os melhores resultados os valores obtidos
através da validação houldout.

### Classificação

Para os algoritmos de clasificação o que obteve o melhor resultado foi a Random Forest com as seguintes métricas:

#### acurácia: 0.9628084810566563; precisão: 0.9721314451706609, recall: 0.9422789265288165 e F1_score: 0.956972431973549

### Regressão

Para os algortimos de regressão não obtiveram um bom resultado com a validação houldout. Sendo os seus melhores resultados
obtidos através dos testes com o dataset de treino.

### Clusterização 

O K MEANS foi o algoritmo que obteve o melhor resultado.
#### Silhouette Score: 0.23295918228054466

