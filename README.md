# Containers de bancos de dados

- Objetivo: Oferecer orquestrador de containers Docker para diversos bancos de dados e gerenciadores compativeis com os mesmos, de modo a ter acesso ao banco de dados de forma rapida, possibilitando agilidade no desenvolvimento de projetos.
<br>
<br>

___
##  Como usar?
Inicialmente abra o Docker em seu compudator. Posteriormente, dentro do repositório _**Database**_ navegue até o diretório do banco desejado, exemplo: ``cd .\Mongo_MongoExpress\`` e execute com o comando `docker compose up` no terminal.

Pronto! Seu banco estará criado e pode ser visualizado através do gerenciador na porta indicada dentro do arquivo _**docker-compose.yml**_, exemplo http://localhost:8081 para MongoDb.

Observações:
-   Credenciais e *strings* de conexão para cada banco estão no arquivo _**docker-compose.yml**_ de cada banco;
- Caso queira que o banco ligue automaticamente, descomente as linhas `restart: always`.