Projeto: Análise e Modelagem de Dados com Regressão Linear

Este repositório contém dois notebooks que abordam diferentes aspectos da análise de regressão linear usando dados reais. O foco está na aplicação de técnicas de Machine Learning para prever variáveis dependentes a partir de variáveis independentes, utilizando abordagens como validação cruzada e k-fold.

Notebooks

1. Leonardo_Meduna_LAB_04.ipynb

Este notebook apresenta um processo completo de análise de dados e modelagem utilizando regressão linear.

Passos principais:

Instalação de bibliotecas: Uso da biblioteca ucimlrepo para carregar datasets.

Exploração de dados: Carregamento e pré-processamento, incluindo identificação e conversão de variáveis categóricas para formato binário.

Treinamento do modelo: Teste de diferentes combinações de variáveis independentes para otimizar a performance do modelo.

Avaliação do modelo: Cálculo de métricas como R², MAE, MAPE, MSE e RMSE.

Conclusão: O modelo apresentou baixo desempenho devido à fraca correlação entre as variáveis independentes e a variável dependente area.

2. kfold_lm_regression.ipynb

Este notebook foca na implementação da técnica de validação cruzada k-fold para a modelagem de regressão linear.

Passos principais:

Instalação de bibliotecas.

Divisão de dados: Uso do k-fold para criar múltiplos subconjuntos de treino e teste, garantindo uma avaliação mais robusta do modelo.

Treinamento e validação: O modelo é treinado e avaliado em cada iteração do k-fold.

Avaliação final: O modelo mostrou baixo desempenho, com altas taxas de erro (MAPE elevado), indicando a necessidade de ajustes ou mais dados.

Conclusões

Ambos os notebooks destacam a importância de avaliar a correlação entre variáveis ao treinar modelos preditivos. Os resultados indicaram que as variáveis independentes utilizadas não foram adequadas para explicar a variável dependente com precisão, conforme evidenciado pelos baixos valores de R² e altas taxas de erro nas métricas MAE, MAPE, MSE e RMSE.

Requisitos

Python 3.x

Bibliotecas:

ucimlrepo

pandas

numpy

scikit-learn

matplotlib
