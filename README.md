# ML-Venda-Veiculos

## Objetivo: 
> Realizar previsão do preço de veiculo usandos .</br>
> Este Dataset foi obtido no Kaggle</br>
> Link do Dataset: https://www.kaggle.com/nileshtiwari7/1000-used-car-price-data
> 
## Estudo:
> Neste estudo, foi utilizada a função gridsearch do sklearn para obter o melhor paramentro do modelo. </br>
> Assim foram selecionados os segunites Algoritmos para este estudo: </br>
>* Linear Regression </br>
>* K-Neighbors Regressor </br>
>* Decision Tree Regressor </br>

## Variaveis de Estudo
>* Variavel Target: **Preço do Veiculo Usado** </br>
>* Variaveis independentes (Features): Quilometragem do Veiculo


## Conclusão: 
> Foi Observado que a unica Feature que poderia ser utilizada é a variavel Quilometragem, pois as outras variaveis possui elementos de Data Leakage,
> Logo, tendo o algoritmo KNN como o melhor modelo, com parametro de numero de vizinhaça igual a  6 e Score de 0.30
> 
