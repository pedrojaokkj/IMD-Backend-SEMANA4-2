# IMD-Backend-SEMANA4-2
Atividade de criação de servidor usando node.js

Crie um servidor web com auxílio do Express a partir do que você aprendeu nas Aulas 06 que salve e obtenha as informações de um banco de dados, com auxílio do ORM Sequelize. O programa deve implementar uma API para cadastro e consulta de produtos, conforme detalhamento a seguir.

Esta atividade é uma extensão da atividade da aula anterior, adicionando a parte de banco de dados.

Os produtos devem possuir os campos nome, descrição e preço.
Os campos “nome” e “descrição” devem ser textuais
O campo preço deve ser numérico
O campos nome e preço são de cadastro obrigatório
Utilize a biblioteca ajv para validação (https://ajv.js.org/guide/getting-started.html) 
As validações devem ser implementadas como um middleware do Express 
As seguintes rotas devem estar disponíveis
a. GET /produtos – Lista os produtos cadastrados em formato JSON
b. POST /produtos – Cadastra um produto
c. PUT /produtos/:id – Atualiza os dados de um produto
d. DELETE /produtos/:id – Remove determinado produto
Esta atividade é uma extensão da atividade da aula anterior, adicionando a parte de banco de dados.
