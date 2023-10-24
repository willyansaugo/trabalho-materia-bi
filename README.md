# Banco de Dados de Locação

Este repositório é um trabalho da matéria de BI (Business Intelligence) contém um script SQL para criar um banco de dados que armazena informações sobre uma locadora e seus clientes. O banco de dados é projetado para permitir o armazenamento de detalhes sobre locadora de filmes.

## Arquivos SQL
Dentro do diretório ./ estão localizados os arquivos:

- `dw-bi.sql`: Este script cria o banco de dados `DW-BI` após ETL, com as tabelas necessárias, como Clientes, Filmes, Pagamento e Tempo de Locação, e os dados relacionadas a tabela.
- `Dockerfile`: Este arquivo parametriza a criação do container no Docker Desktop.
- `Matriz Dimensão X Indicador`: É a tabela que iremos fazer antes de gerar nossos gráficos e dashboards no Power BI.

No diretório ./DW Star Schema estão localizados os arquivos:
- `DW-BI`: É o nosso data warehouse depois de ter sido transformados no ETL, ali estão armazenados nossos inserts e selects de todas as tabelas.

No diretório ./ETL estão localizados os arquivos:
- Ali está localizado nossas transformações de cada tabela pelo ETL, além disso, temos a tabela fato gerada e o Job (erado por 24hrs).

No diretório ./Fonte de Dados BD estão localizados os arquivos:
- Ali está localizado nossas fontes de dados que foram usadas durante as transformações do ETL.

## Uso

mysql:8.0.16
Docker Desktop
