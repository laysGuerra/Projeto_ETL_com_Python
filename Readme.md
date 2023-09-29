
# Projeto de ETL de Dados com Python e SQL

Este é um projeto para a disciplina de Explorando a IA Generativa com Python do Bootcamp Ciencia de dados com Python feito em parceria da DIO com o Santander.

Neste repositório eu criei um Pipeline de ETL com Python, que extrai dados de um csv, transforma ele adicionando uma nova coluna com uma mensagem e carrega para um banco de dados.

Criei uma simples database no SQLServer com uma tabela contendo o ID, o nome, a idade e mensagem que será implementada no nosso script, dessa forma:

![imagem](https://media.discordapp.net/attachments/1024076211137290270/1157191311770787870/image.png?ex=6517b5e4&is=65166464&hm=8ef6e2009ad78ab5a75ed789b8a4d594d5febd5e5202369bd71af48ed44ab590&=
)


### Extract
Na Etapa de extração, utilizaremos o pandas para extrair dados de usuários ficticios para um DataFrame, neste arquivo csv tem o id, o nome e a idade dos nossos usuários.

### Transform
Nesta etapa, vamos percorrer o df criando uma variável de mensagem para cada linha e adicinando essa coluna de mensagem no DataFrame.

### Load
Por fim, na etapa de Load inserimos os dados com o cursor para cada linha do nosso df ser adicionada no banco de dados, commitamos e fechamos o cursor

Após a etapa de Carregamento, verificando a nossa pequena base de dados podemos conferir que os dados foram adicionados na tabela indicada.

![imagem](https://media.discordapp.net/attachments/1024076211137290270/1157193067179298878/image.png?ex=6517b786&is=65166606&hm=ca019a202a88db8a683ed7ba0dade9a5f43d8004d440376c48af02a8c2a6990d&=)


















