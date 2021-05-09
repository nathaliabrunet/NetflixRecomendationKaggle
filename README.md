# Netflix Movie Recomendation

<img src="Figures/netflix.png">

## Tópicos 

[Descrição](#Descrição)

[Dadaset](#Dadaset)

[Passo a Passo](#Passo-a-Passo)

[Estrutura do Diretório](#Estrutura-do-Diretório)

[Ferramentas utilizadas](#Ferramentas-utilizadas)


## Descrição

Problema de recomendação de filmes com base em dados da Netflix. A ideia é prever se alguém vai gostar de um filme para realizar a recomendação.

Obs:
Projeto abordado no curso Machine Learning realizado pela Data Science Academy (DSA)
link: https://www.datascienceacademy.com.br/

## Dadaset

Conjunto de dados da concorrência da Netflix para melhorar seu algoritmo de recomendação. 
O dataset pode ser baixado no desafio do kaggle: https://www.kaggle.com/netflix-inc/netflix-prize-data

Arquivos:
combined_data_1.txt
combined_data_2.txt
combined_data_3.txt
combined_data_4.txt
movie_titles.csv

A primeira linha de cada arquivo txt (ex: combined_data_1.txt) contém o id do filme seguido por dois pontos. 
Cada linha subsequente no arquivo corresponde a uma avaliação de um cliente e sua data.

Formato
Id do filme:
Id do cliente, avaliação, data

Ex:

<img src="Figures/cara txt.png">

As avaliações estão em uma escala de cinco estrelas (integral) de 1 a 5.
As datas têm o formato AAAA-MM-DD.

## Passo a Passo

1. step1-Criando csv
Na primeira etapa é realizada a junção dos 4 arquivos txts e criação de um único csv chamado "dataset.csv"

csv gerado tem essa cara:

<img src="Figures/cara csv.png">

2. step2-EDA

	Análise exploratória dos dados
	Criação da matriz esparsa
	Problemas de cold start
	Cálculo de similaridade
	Redução de dimensionalidade com TruncatedSVD

3. step3-ML 
Terceira etapa é a implementação do modelo de recomendação.

## Estrutura do Diretório
```
```
## Ferramentas utilizadas
* Jupyter notebook
* Python