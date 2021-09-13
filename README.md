# fit

###### Conjunto de Dados - COVID, FLU, COLD Symptoms - https://www.kaggle.com/walterconway/covid-flu-cold-symptoms
* Resumo dos dados - https://github.com/janeptn/fit/blob/main/Dataset_Info.ipynb

###### 1) Implemente 2 ou mais algoritmos com scikit learn para o diagnóstico destas doenças. 

* KNN - https://github.com/janeptn/fit/blob/main/Scikit_learn_KNN.ipynb
* SVM - https://github.com/janeptn/fit/blob/main/Scikit_learn_SVM.ipynb
* Naive Bayes - https://github.com/janeptn/fit/blob/main/Scikit_learn_NV.ipynb
* Decision Tree - https://github.com/janeptn/fit/blob/main/Scikit_learn_DecisionTree.ipynb

###### 2) Implemente pelo menos 1 algoritmo classificador com redes neurais em Pytorch ou Tensorflow (Keras não é permitido).

* Pytorch - https://github.com/janeptn/fit/blob/main/PyTorch_NN.ipynb

###### 3) Implemente um ensemble dos modelos anteriores, justifique suas escolhas.

* Ensemble implementado através do método de Votação, classe VotingClassifier do Scikit_Learn. 
* Esemble - https://github.com/janeptn/fit/blob/main/Scikit_learn_EnsembleVoting.ipynb

###### 4) Avalie o resultado dos experimentos e a acurácia do seu modelo.

De maneira geral, os métodos de classificação apresentaram acurácia muito parecida ao lidar com o desafio de classificação do conjunto de dados COVID, FLU, COLD Symptoms.
Analisando os resultados, é possível notar que todos os métodos tiveram dificuldades em lidar com o desbalanceadas das classes, as classes ALLERGY e FLU eram predominantes.
Nota-se que os métodos Naive Bayes e SVM tiveram melhor desempenho ao classificar as classes minoritárias COVID e COLD em relação a Precisão e Revocação.

Nos testes realizados com o método de Ensemble de Classificadores - VotingClassifier disponível no Scikit_Learn.
A abordagem Voting, considera a predição que receber a maior quantidade de votos como a escolhida. Com o objetivo de obter um resultado de classificação que apresentasse maior robustes, foram selecionados métodos de classificação com características distintas (heterogêneos): 

     - Árvores de Decisao - entropia
     - Nayve Bayes - probabilístico
     - KNN - classificador baseado em instâncias
     
Nota-se resultados equivalente ao método Naive Bayes, em especial, ao utilizar a abordagem de Sampling para lidar com o desbalanceamento entre as classes no conjunto de treinamento.








