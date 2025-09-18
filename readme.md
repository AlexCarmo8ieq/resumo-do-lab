Como eu criei um banco de dados SQL no Azure
1. Acesso ao portal
Primeiramente, eu acessei o Azure Portal com minha conta pessoal. Já logado, fui direto ao menu lateral e cliquei em "Criar um recurso".

2. Escolha do tipo de banco
Dentro da seção de criação, selecionei "Banco de dados" > "SQL Database". Essa opção me permitiu criar um banco relacional gerenciado, ideal para aplicações que usam T-SQL.

3. Configuração inicial
Na tela de configuração:

Criei um novo grupo de recursos chamado rg-database-test, para manter os recursos organizados.
Dei o nome db-clientes-prod ao banco.
4. Criação do servidor SQL
Como ainda não havia um servidor SQL disponível, cliquei em "Criar novo":

Nomeei o servidor como sql-server-prod
Defini um login de administrador (adminsql) e uma senha forte
Escolhi a região Brazil South, por estar mais próxima da minha operação em São José dos Pinhais
5. Escolha do modelo de compra
Optei pelo modelo vCore-based, pois precisava de mais controle sobre CPU, memória e escalabilidade. Escolhi a camada General Purpose, com 2 vCores e 32 GB de armazenamento, suficiente para o volume inicial de dados.
