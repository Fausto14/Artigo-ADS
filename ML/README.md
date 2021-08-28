# Artigo ADS
## Implementações dos Algoritmos de Aprendizagem de Máquina

- Trabalho desenvolvido para a disciplina de Análise de Desempenho de Sistemas do programa de Mestrado e Doutorado em Ciência da Computação - MDCC/UFC. 
- O objetivo é apresentar uma análise de desempenho de modelos de aprendizagem de máquina, a fim de que esses modelos aplicados, auxiliem o projetista de um produto de sistema visão computacional escolher o melhor modelo para a tarefa de classificação da qualidade do couro caprino a partir de resultados de métricas de avaliação.

## Algoritmos de Aprendizagem de Máquina
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Multilayer Perceptron (MLP)
- Regressão Logística (RL)
- [Minimal Learning Machine (MLM)](https://doi.org/10.1016/j.neucom.2014.11.073)

## Métricas Avaliadas
- Acurácia
- Especificidade
- Precisão
- Sensitividade
- f(0,5)-Score
- Tempo total de treinamento e teste do processo de aprendizagem.

## Recursos
- Implementação desenvolvida em um ambiente virtual `Jupyter Notebook`
- `Python` versão 3.7.7 e a biblioteca [Scikit-Learn](http://scikit-learn.org/).

## Implementações
As implementação foram separadas nas sequintes pastas:
- ** Util ** contém uma classe para auxiliar na divisão e manipulação do dataset.
- ** dataset ** contém um `Jupyter Notebook` `.ipynb` que apresenta os tratamentos de preparação dos dados.
- ** knn ** contém um `Jupyter Notebook` `.ipynb` que apresenta a implementação do modelo KNN.
- ** mlm ** contém um `Jupyter Notebook` `.ipynb` que apresenta a implementação do modelo MLM.
- ** mlp ** contém um `Jupyter Notebook` `.ipynb` que apresenta a implementação do modelo MLP.
- ** regressao_logistica ** contém um `Jupyter Notebook` `.ipynb` que apresenta a implementação do modelo Regressão Logística.
- ** svm ** contém um `Jupyter Notebook` `.ipynb` que apresenta a implementação do modelo SVM.

Na pasta de cada modelo contém um arquivo no formato CSV que apresenta os resultados das métricas utilizadas na análise de desempenho dos modelos nas 50 rodadas/iterações.

## Resultados
- Na pasta ** resultados ** contém um `Jupyter Notebook` `.ipynb` que uni os resultados do modelos e gera as tabelas, box plots e matrizes de confusão dos experimetos.

			
## Instalação
- Entrar no [diretório raiz do respositório](https://github.com/Fausto14/Artigo-ADS) e baixar ou clonar o projeto.
- Após obter o projeto, carregue-o em qualquer ferramenta que interprete notebooks `.ipynb`. Depois, acessar as pastas que contém as implementações dos modelos e executar os notebooks.

## Autores
- [Fausto Sampaio](https://github.com/Fausto14) 
- [Lailson Azevedo do Rego](#)
