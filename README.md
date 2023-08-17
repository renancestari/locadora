# Projeto
Este projeto simula uma locadora de filmes que deseja utilizar um modelo de Machine Learning para classificar filmes em três categorias.

# Introdução 
Durante meu curso na faculdade, tive a oportunidade de adentrar ao universo do machine learning.

# Questão a se seguir
Uma locadora de filmes deseja utilizar um modelo de machine learning para classificar filmes em três categorias: Ação, Romance e Comédia.

A locadora possui um conjunto de filmes para classificar, e eles escolheram as seguintes características para coletar dados inicialmente:

1 - Quantidade de cenas de ação: Representada por um valor numérico inteiro.

2 - Quantidade de cenas românticas: Representada por um valor numérico inteiro.

3 - Quantidade de cenas engraçadas: Representada por um valor numérico inteiro.

Com base nessas características, eles coletaram dados de treinamento para construir o modelo de Árvore de Decisão.

Dados de Treinamento:

Filme 1: 15 cenas de ação, 5 cenas românticas, 2 cenas engraçadas - Categoria: Ação

Filme 2: 3 cenas de ação, 10 cenas românticas, 8 cenas engraçadas - Categoria: Romance

Filme 3: 2 cenas de ação, 2 cenas românticas, 20 cenas engraçadas - Categoria: Comédia

Com base nesses dados de treinamento, desenvolva um modelo de Árvore de Decisão que será treinado para aprender a realizar a classificação correta dos filmes com base nas características fornecidas.

Após o treinamento do modelo, realize o teste com um novo filme:

Dados de teste:

Filme Teste: X cenas de ação, X cenas românticas e X cenas engraçadas.

Resposta: O modelo deve classificar esse filme como "X".

# Estrutura

from sklearn.tree import DecisionTreeClassifier

#Dados de treinamento

Aqui você incluirá os dados de treino em uma variável e a resposta em outra, como apresentado no enunciado. 

#Criação do modelo de Árvore de Decisão

Aqui você deve incluir o código que cria/chama o modelo da Árvore de Decisão

#Treinamento do modelo

Aqui você deve incluir o código que realiza o treinamento do modelo.

#Dados de teste

Aqui você incluirá os dados de teste como apresentado no enunciado. 

#Classificação dos filmes de teste

Aqui você deve incluir o código que realiza a lógica da previsão.

#Exibição da categoria atribuída ao filme teste

Aqui você deve incluir a lógica que imprime o resultado do teste (print).
