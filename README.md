# Previsão de Notas em Matemática
Este projeto teve como objetivo criar modelos de machine learning capazes de prever as notas de matemática de estudantes com base em dados coletados previamente. Para alcançar esse objetivo, utilizamos pacotes em Python como numpy, pandas, seaborn, sklearn e matplotlib, dentro do ambiente de desenvolvimento jupyter notebook.

Análise Exploratória dos Dados:

Iniciamos o projeto carregando os dados e verificando se havia valores nulos ou tipos de dados incompatíveis. As variáveis numéricas foram descritas através do método describe e as variáveis categóricas foram transformadas em numéricas utilizando as técnicas de Label Encoding e One-Hot Encoding. Uma tabela e um mapa de correlação foram criados para analisar as relações entre as variáveis.

Modelagem de Machine Learning:

Os dados foram divididos em treino e teste e utilizamos um modelo de regressão linear simples para prever as notas de matemática. Foram realizados testes com outros modelos, como ridge e lasso, mas o modelo de regressão linear simples apresentou resultados semelhantes e foi escolhido como melhor opção.

Avaliação do Modelo:

O modelo de regressão linear simples apresentou um desempenho satisfatório, com um MAE de 4.55, RMSE de 5.67, R2 de 0.85 e variância explicada de 0.85. Os resíduos apresentaram uma distribuição próxima da normalidade. Verificamos visualmente as diferenças entre o valor previsto e o valor observado através de um gráfico e calculamos os valores de erro (MAE, RMSE, R2 e variância explicada).

MSE: é uma métrica que mede a média dos erros ao quadrado entre os valores previstos pelo modelo e os valores reais. 

RMSE: é a raiz quadrada do MSE e fornece uma medida da dispersão dos erros. Ela tem a mesma unidade da variável dependente, o que facilita a interpretação.

R2: é uma medida estatística que representa a proporção da variabilidade dos dados que é explicada pelo modelo. É um valor entre 0 e 1 e quanto mais próximo de 1, melhor é o modelo em explicar a variação dos dados.

Variância explicada: é a proporção da variância total dos dados que é explicada pelo modelo. É uma medida similar ao R2, mas é expressa em termos percentuais.

MAE: é uma métrica que mede a média dos erros absolutos entre os valores previstos pelo modelo e os valores reais. 

Conclusão:

O modelo de regressão linear simples foi capaz de prever as notas de matemática dos estudantes com uma boa precisão. Considerando que outros modelos testados não apresentaram uma melhoria significativa em relação a este modelo, concluímos que a regressão linear simples é a melhor opção para este tipo de análise. É importante ressaltar que o modelo pode ser aprimorado com a inclusão de mais variáveis ou com o refinamento dos dados disponíveis.
