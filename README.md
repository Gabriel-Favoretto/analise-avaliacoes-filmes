# Análise de Avaliações de Filmes

Esse foi meu primeiro projeto de análise de dados com Python. A ideia aqui foi explorar um conjunto de avaliações de filmes feitas por usuários e começar a entender como trabalhar com bibliotecas como Pandas, Matplotlib e Seaborn.

## Sobre os dados

Os dados foram retirados do [MovieLens 20M Dataset](https://grouplens.org/datasets/movielens/20m/), e usei dois arquivos principais:

- `ratings.csv`: contém as avaliações (notas) dos usuários  
- `movies.csv`: traz os títulos e os gêneros dos filmes

Por enquanto, os arquivos não estão incluídos no repositório por conta do tamanho (o de avaliações tem mais de 250 MB), então é preciso fazer o upload manual no Google Colab para rodar o notebook.

## Como rodar

Você pode abrir e executar o notebook direto no Google Colab pelo link abaixo:

[🔗 Abrir no Google Colab](https://colab.research.google.com/github/Gabriel-Favoretto/analise-avaliacoes-filmes/blob/main/Análise_de_Dados_de_Filmes_com_Pandas_(iniciante).ipynb)

> Obs.: os arquivos `ratings.csv` e `movies.csv` precisam ser enviados manualmente ao Colab.

## O que foi analisado

- Distribuição das notas dadas pelos usuários  
- Evolução da quantidade de avaliações ao longo do tempo  
- Filmes mais avaliados  
- Comparação entre popularidade (quantidade de avaliações) e nota média  
- Filmes que mantêm nota alta mesmo com grande volume de avaliações  

## Principais insights

- A maioria das notas fica entre 3 e 5, mostrando uma tendência mais positiva nas avaliações  
- O volume de avaliações se manteve relativamente estável ao longo dos anos  
- Filmes mais avaliados nem sempre têm as melhores notas  
- Alguns filmes, como *The Shawshank Redemption*, conseguem manter nota média alta com muitas avaliações  

## Ferramentas utilizadas

- Python  
- Google Colab  
- Pandas  
- Matplotlib  
- Seaborn

## Autor

Gabriel Favoretto  
[LinkedIn](https://www.linkedin.com/in/gabriel-favoretto-636a60173/)



