# DIO - Trilha .NET - Banco de Dados
www.dio.me

## Desafio de projeto
Para este desafio,utilizei meus conhecimentos adquiridos no módulo de banco de dados, da trilha .NET da DIO.
Utilizei o DBeaver e o terminal para fazer consultas e executar os scripts
Utilizei sistema operacional Linux

## Contexto
Você é responsável pelo banco de dados de um site de filmes, onde são armazenados dados sobre os filmes e seus atores.
Sendo assim, foi solicitado para que você realize uma consulta no banco de dados com o objetivo de trazer alguns dados para análises.

## Proposta
Você precisará realizar 12 consultas ao banco de dados, cada uma retornando um tipo de informação.
O seu banco de dados está modelado da seguinte maneira:
![diagrama](https://github.com/user-attachments/assets/3cfa1eba-82e1-4e27-ae26-c4cf2577792a)


As tabelas sao descritas conforme a seguir:

**Filmes**

Tabela responsável por armazenar informações dos filmes.

**Atores**

Tabela responsável por armazenar informações dos atores.

**Generos**

Tabela responsável por armazenar os gêneros dos filmes.

**ElencoFilme**

Tabela responsável por representar um relacionamento do tipo muitos para muitos entre filmes e atores, ou seja, um ator pode trabalhar em muitos filmes, e filmes
podem ter muitos atores.

**FilmesGenero**

Tabela responsável por representar um relacionamento do tipo muitos para muitos entre filmes e gêneros, ou seja, um filme pode ter mais de um gênero, e um genêro pode fazer parte de muitos filmes.

## Preparando o banco de dados
Você deverá executar o arquivo **Script Filmes.sql** em seu banco de dados SQL Server, presente na pasta Scripts deste repositório ([ou clique aqui](Script%20Filmes.sql)). Esse script irá criar um banco chamado **Filmes**, contendo as tabelas e os dados necessários para você realizar este desafio.

## Objetivo
Criar diversas consultas, com o objetivo de retornar os dados a seguir. 
Abaixo de cada pedido tem o retorno esperado. O seu retorno deve ser igual ao da imagem.

## 1 - Buscar o nome e ano dos filmes
![1](https://github.com/user-attachments/assets/a690665e-b8b7-482c-9227-d82afec185b2)



## 2 - Buscar o nome e ano dos filmes, ordenados por ordem crescente pelo ano

![2](https://github.com/user-attachments/assets/c4d5ddcf-0e0d-41cc-ae7a-314c156e3c02)

## 3 - Buscar pelo filme de volta para o futuro, trazendo o nome, ano e a duração

![3](https://github.com/user-attachments/assets/74d9dd3c-6c5f-4ad2-ae2f-0fb4e8b45b2e)

## 4 - Buscar os filmes lançados em 1997
![4](https://github.com/user-attachments/assets/a454e7d4-3719-413b-a283-a8b01a09ca2f)



## 5 - Buscar os filmes lançados APÓS o ano 2000
![5](https://github.com/user-attachments/assets/42085277-9ea6-4492-992a-e520d4582370)

![5](https://github.com/user-attachments/assets/353cf711-acb6-4c38-8aba-8ea69ead79b3)

## 6 - Buscar os filmes com a duracao maior que 100 e menor que 150, ordenando pela duracao em ordem crescente

![6](https://github.com/user-attachments/assets/adaf52f7-d439-47a1-ba88-11d5db22a867)


## 7 - Buscar a quantidade de filmes lançadas no ano, agrupando por ano, ordenando pela duracao em ordem decrescente

![7](https://github.com/user-attachments/assets/1f3516c8-5693-4be5-83c1-a22c75bcecc8)


## 8 - Buscar os Atores do gênero masculino, retornando o PrimeiroNome, UltimoNome
![8](https://github.com/user-attachments/assets/6dc3ebc1-5566-44a8-a1f6-318adf8bccc2)

## 9 - Buscar os Atores do gênero feminino, retornando o PrimeiroNome, UltimoNome, e ordenando pelo PrimeiroNome

![9](https://github.com/user-attachments/assets/29b78dc4-d0ed-4aba-9c81-d6c5756116dd)


## 10 - Buscar o nome do filme e o gênero
![10](https://github.com/user-attachments/assets/ef43184f-2b49-41ff-904c-92104c6fde92)


## 11 - Buscar o nome do filme e o gênero do tipo "Mistério"

![Exercicio 11](Imagens/11.png)

## 12 - Buscar o nome do filme e os atores, trazendo o PrimeiroNome, UltimoNome e seu Papel


