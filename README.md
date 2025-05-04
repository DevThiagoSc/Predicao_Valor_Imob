# Predição do valor de imóveis na cidade de São Paulo

O projeto tem como objetivo comparar 3 modelos de regressão para prever os valores de imóveis, com base em treinamento de registros feitos nos anos de 2017 e 2018.


Foram comparados os seguintes modelos:

* Regressão Lasso: apresentou uma boa capacidade de explicação, porém um alto RMSE devido a heterocedasticidade dos resíduos.
  
* Random Forest: Com um modelo que lida melhor com heterocedasticidade, houve uma ótimca capacidade de explicação dos registros, além de ganhar diminuição do valor do RMSE, entretanto o modelo teve dificuldades para lidar com imóveis de alto padrão, fazendo com que na faixa de valores acima de R$ 800k houvesse aumento de altos valores de resíduos.
  
* Um terceiro modelo foi uma Random Forest, porém com dados de treino com imóveis de até 800K, resultando numa pequena queda de explicabilidade porém uma ótimqa melhora do RMSE. 
