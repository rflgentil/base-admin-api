# Base admin API

## Docker/Postgres

-   Instalar o [Docker](https://docs.docker.com/)
-   Criar container pela imagem do **[postgres](https://hub.docker.com/_/postgres)** é só rodar `docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres`
-   Rodar as migrations `yarn sequelize db:migrate` (_Não esquecer de criar o banco com o nome de: baseadmin_)

## Yarn

-   Instalar o [yarn](https://classic.yarnpkg.com/pt-BR/docs/install/#mac-stable)
-   Rodar `yarn` para instalar as dependencias do projeto

## Rodando a aplicação

-   Rodar `docker start database` para rodar o container do **postgres**
-   Rodar `yarn dev` para iniciar o projeto
