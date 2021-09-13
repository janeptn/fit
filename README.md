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
* Considera a predição que receber a maior quantidade de votos como a escolhida;
* A escolha tem como objetivo obter um resultado de classificação que apresente maior robustes, foram selecionados métodos de classificação com características distintas (heterogêneos): 

     - Árvores de Decisao - entropia
     
     - Nayve Bayes - probabilístico
     
     - KNN - classificador baseado em instâncias

###### 4) Avalie o resultado dos experimentos e a acurácia do seu modelo.
