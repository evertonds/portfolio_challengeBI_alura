# 2ª edição - Alura Challenge BI 

Projetos apresentados durante o segundo Alura Challenge BI, desenvolvidos em Fevereiro/2022. 

O desafio é composto de atividades divididas em três semanas, onde em cada semana, uma base de dados diferente é utilizada para criação de dashboards e insights sobre diferentes temas. 

Meus objetivos pessoais ao construir esse repositório e participar desse desafio é aumentar meus conhecimentos relacionados à ciência de dados. 

# 1ª Semana

As informações iniciais e arquivos foram compartilhados no Trello, ferramenta que eu não possuia conhecimento de como utilizar, mas que se provou realmente útil e intuitiva ao primeiro contato. 

O primeiro projeto consiste em analisar uma base de dados de filmes provenientes do IMDB, e a retirar insights acerca dessas informações. 

Ao realizar o download das bases de dados, que se encontram nos diretórios do repositório, foi analisado a estrutura, tipo dos dados e possíveis problemas nas bases de dados. 

Notou-se que alguns valores da coluna de faturamento dos filmes estavam vazios. Com isso, foi realizado uma média simples entre os filmes de mesmo genero, e a partir dos valores encontrados, as lacunas de dados faltantes foram preenchidas com os valores médios encontrados para o mesmo genero. Essa base de dados foi nomeada como Filmes_base. 

Numa segunda etapa, foi identificado que na coluna que continha os generos dos filmes, alguns apresentavam 2 ou 3 generos, separados por virgula. Para facilitar a tratativa dos dados posteriormente, optou-se por carregar novamente a base de dados, excluir todas as colunas a não ser a ID_title, a Serie_Title e a coluna Genre. Separou-se a coluna Genre em outras linhas, para que pudesse ser encontrado a quantidade máxima de generos contidos na base de dados. Essa base de dados foi nomeada como Filmes_genero. 

Prosseguiu-se com o mesmo procedimento para as colunas que continham o nome dos atores que participaram dos filmes. Existiam 4 colunas, e era necessário que essas fossem empilhadas, para que se soubesse quanto cada ator rendeu de faturamento no total dos filmes. Essa base de dados foi nomeada como Filmes_atores. 

Há também uma base de dados que traz as informações dos posters dos filmes, que foi utilizada para ilustração da dashboard. 



