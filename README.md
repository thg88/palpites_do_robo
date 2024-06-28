# palpites_do_robo

# Descrição do Projeto

Projeto criado com o intuito de realizar a previsão de partidas de futebol utilizando um dataset (BRA.csv) com histórico de jogos do Campeonato Brasileiro de 2012 a 2024 utilizando 3 métodos de machine learning supervisionado (Random Forest, SVC e Logistic Regression).

Há também um dataset (matches.csv) com dados dos jogos da Premier League que foi utilizado nos primeiros testes. Os datasets possuem informações diferentes, onde o matches.csv possuem estatísticas a respeito das partidas enquanto o dataset BRA.csv possui informações das odds das principais casas de apostas online, onde através dos testes foi verificado que o segunda dataset possuia uma melhor taxa de acerto, já que as odds representam de forma genérica dados relevantes, como o momento das equipes, valor de mercado, tradição, entre outros fatores que acabam por definir um favorito a vencer a partida através das apostas.


# Conteúdo do repositório

**matches.csv**;
**BRA.csv**

Arquivo csv com os dados já estruturados.

**prediction.ipynb**;
**Random Forest.ipynb**;
**SVC.ipynb**;
**Logistic Regression.ipynb**

Arquivo com o algoritmo e todos o passo-a-passo usado para chegar ao resultado.

**scraping.ipynb**

Passo-a-passo para a extração e manipulação dos dados para deixá-los pronto para uso no algoritmo.



