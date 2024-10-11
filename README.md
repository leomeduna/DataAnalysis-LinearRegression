Projeto: Análise e Modelagem de Dados com Regressão Linear
Este repositório contém dois notebooks que abordam diferentes aspectos da análise de regressão linear usando dados reais. Os notebooks focam em como aplicar técnicas de Machine Learning para prever variáveis dependentes com base em variáveis independentes, utilizando abordagens como validação cruzada e k-fold.

Notebooks
##1. Leonardo_Meduna_LAB_04.ipynb
Este notebook abrange um processo completo de análise de dados e modelagem usando regressão linear.

Primeiros passos:
Instalação de bibliotecas necessárias: ucimlrepo para carregar datasets.
Exploração de dados:
Carregamento e pré-processamento de dados, incluindo a identificação de variáveis categóricas e a conversão dessas variáveis para o formato binário.
Treinamento do modelo:
Utilização de várias combinações de variáveis independentes para determinar a melhor performance do modelo.
Avaliação do modelo:
Cálculo de métricas como R², MAE, MAPE, MSE e RMSE, que indicam a performance do modelo. Os resultados indicaram baixa correlação entre as variáveis independentes e a variável dependente area, resultando em um modelo com desempenho insatisfatório.

##2. kfold_lm_regression.ipynb
Este notebook foca na implementação de uma abordagem de validação cruzada k-fold para a modelagem de regressão linear.

Primeiros passos:

Instalação de bibliotecas necessárias.
Divisão de dados:

Aplicação da técnica de k-fold, dividindo os dados em múltiplos subconjuntos de treino e teste para avaliar a robustez do modelo.
Treinamento e validação:

Treinamento e validação do modelo em cada iteração do k-fold, resultando em múltiplas métricas de desempenho.
Avaliação final:

O modelo foi considerado inadequado devido a uma baixa correlação entre as variáveis e altos valores de erro (como o MAPE elevado). A conclusão foi que o modelo precisaria de ajustes ou mais dados para melhorar sua performance.
Conclusões
Ambos os notebooks demonstram a importância de se avaliar as correlações entre variáveis ao se treinar modelos preditivos. Em ambos os casos, a análise indicou que as variáveis independentes não eram adequadas para explicar a variável dependente com precisão. Isso é evidenciado pelos baixos valores de R² e altos valores de erro nas métricas MAE, MAPE, MSE e RMSE.

Requisitos
Python 3.x
Bibliotecas:
ucimlrepo
Pandas
NumPy
Scikit-learn
Matplotlib
