# DockerMySql
Para iniciar o container. As variáveis serão:
MYSQL_ROOT_PASSWORD: Senha para acessar o banco dentro do container;
MYSQL_DATABASE: Banco de dados a ser criado;
MYSQL_USER: Usuário para ter acesso ao banco de dados;
MYSQL_PASSWORD: Senha do usuário para ter acesso ao banco de dados;

# Docker Run
docker run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=RootPassword -e MYSQL_DATABASE=Database -e MYSQL_USER=MainUser -e MYSQL_PASSWORD=MainPassword nome-container