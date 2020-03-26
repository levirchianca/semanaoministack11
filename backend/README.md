# Semanaoministack, be-the-hero
Projeto desenvolvido durante a semana oministack, que consiste em um sistema completo(api, site e app) para que ongs possam receber doações para executar seus projetos.

## Inicializar banco
Para aplicar as migrações e consequentemente crir o nosso banco de dados, rode o seguinte comando:

    $ npx knex migrate:latest

Para validar que todas as migrações foram aplicadas, rode o seguinte comando:

    $ npx knex migrate:status

## Levantar servidor/API
Para statar nosso servidor/api basta executar o seguinte comando:

    $ npm start

## Rotas
 - `/ongs`: Cadastrar, listar e deletar ongs.
 - `/incidents`: Cadastrar, listar todos os incidentes e deletar incidente.
 - `/sessions`: Efetuar login de uma ong.
 - `/profile`: Listar todas os incidentes cadastrados por uma ong.