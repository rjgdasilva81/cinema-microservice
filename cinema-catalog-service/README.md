1) Na pasta data armazenaremos os dados do nosso banco MongoDB (basta apontar o dbpath para cá na inicialização do banco) deste microserviço.
2) Na pasta src armazenaremos os códigos-fonte do mesmo.
3) Lembre-se de não versionar as pastas de dados, a node_modules e o arquivo .env de cada microserviço, adicionando os seus respectivos caminhos no seu .gitignore.
4) Na pasta api amazenaremos o código para tratamento das requisições http do microserviço.
5) Na pasta config armazenaremos o módulo de conexão com o banco de dados do microserviço
6) Na pasta repository armazenaremos a camada de acesso aos dados do microserviço, obedecendo ao pattern Repository, que nada mais é que uma versão mais "NoSQL" do pattern DAO (Data Access Object)
7) Na pasta server armazenaremos o servidor de cada microserviço, afim de garantir que cada microserviço tenha seu servidor instanciado isoladamente.
8) Os arquivos .env e .env.example são os responsáveis por compartilhar as variáveis de ambiente utilizadas pelo microserviço.
9) O package.json é o arquivo descritor de nosso microserviço, contendo todas as suas dependências.
10) O index.js funciona como um orquestrador todos os módulos que compoem o nosso microserviço, sendo o responsável por inicia-lo.