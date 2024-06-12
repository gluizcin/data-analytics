O objetivo deste projeto foi realizar uma análise exploratória com os dados de bilheteria diária das salas de cinema do Brasil. A ideia foi tirar algumas informações que possam ser relavantes acerca das exibições de obras nos cinemas brasileiros.

Para isso, foi utilizado um dataset da ANCINE disponibilizados no link abaixo:
https://dados.gov.br/dados/conjuntos-dados/relatorio-de-bilheteria-diaria-de-obras-informadas-pelas-distribuidoras

Utilizei nessa análise os dados referente ao período de **março de 2019 a março de 2024.**

Para guiar a análise e auxiliar na obtenção de insights, foram respondidas as questões abaixo

- Quais os 10 filmes com maior número de público durante o período registrado na base?
- Quais os 10 filmes brasileiros com maior número de público durante o período registrado na base?
- Quantos filmes nacionais e internacionais foram exibidos?
- Existe uma diferença significativa de publico entre filmes nacionais e internacionais?
- Qual é a média de público por estado?
- Quantos filmes diferentes foram exibidos em cada estado?
- Do período registrado na base, qual ano teve maior público?
- Existem meses específicos com maior público?

Para o tratamento de dados e análises, foram utilizadas as bibliotecas Pandas, Matplotlib e DuckDB do Python.

Este projeto trata-se de um projeto para compor portfólio pessoal, e também tem como objetivo demonstrar conhecimento na linguagem de programação Python, e SQL

Segue abaixo **algumas informações que foram obtidas através da análise**:

- Foram identificados filmes de 64 países diferentes exibidos no período registrado na base, porém, a maioria dos filmes são ou brasileiros ou americanos. Somados, Brasil e EUA possuem 1453 filmes exibidos, enquanto os outros 62 países juntos somam 768 filmes;
- O ano com maior público registrado foi o ano de 2019. Após o início da pandemia em 2020, os números de público voltaram a aumentar a partir de maio de 2021, e desde então vem subindo ano a ano;
- Em média, são exibidos 562 filmes diferentes por ano nos cinemas brasileiros.
