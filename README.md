# hellojs-s03e03

# Exercício / desafio

crie no github um repositório chamado hellojs-s03e03

faça checkout dele na máquina local (consulte aulas passadas ou o universo caso necessite lembrar como é isso)

crie o projeto npm na cópia local deste repositório

salve o knex e o sqlite3 como dependências de projeto

crie um arquivo chamado .gitignore e escreva nele node_modules

pronto seu comit não versionará a node modules
comite o que fizemos até agora para o git

crie uma tabela chamada evento

dos eventos desejaremos saber

descrição do evento
data de início do evento
baseie-se no código fornecido

crie uma coluna chamada idevento para ser a chave primária da tabela evento

a parte de consultas fica maior e mais interessante que isso.

a tarefa é criar mais um arquivo de exemplo de sql e testá-lo no sqlite/db browser

esta consulta deverá fazer uso das funções explicadas aqui

uma consulta que diga quantos participantes cada evento terá
altere os scripts hello-knex-1.js e hello-knex-2.js para fazerem uso do db.js

comite suas alterações para o github

crie um insert usando knex.raw e chame de hello-knex-8.js

você deve receber o nome que deseja incluir

criem:

um migrate com a tabela cachorro
um migrate inserindo 2 cachorros
um migrate adicionando a coluna marcacachorro à tabela
tentem fazer rollback e mudem de ideia de novo
um arquivo a ser executado $ node meuscachorros.js que recebe o nome e a marca do cão e insere o cachorro na tabela
um arquivo a ser executado $ node cademeucatiorro.js que busca um cachorro pelo nome
um migrate com a tabela presenca contendo as colunas usuario, episodio, datapresenca, repo
crie um insert usando knex.raw inserindo um aluno Teste e chame de hello-presenca.js

# Top-top challenge 👾

Utilize a solução do ep S03e02 para realizar inserts na tabela presenca.

# Qual o objetivo?

Ter na tabela presenca todos os participantes que postaram links de repositórios com as implementações até as datas limites.

# Dúvidas?

Prazo para entrega (e postagem do link do repositório na issue S03E03 : 2017-09-18)
