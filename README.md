# API REST
> API REST feita para aprender ExpressJS e Banco de Dados

## Tecnologias
- NodeJS v16
- Express v4.18
- MySQL/MariaDB v8

## Instalação
Para baixar a aplicação execute o seguinte comando em seu terminal:
`git clone https://github.com/digitalcollege-fortal/fs06.git`

Após baixar a aplicação, entre no diretório dela através do terminal e execute:
`npm install` ou `npm i`

## Configuração do Banco de Dados
É necessário configurar as credenciais do banco de dados.

### Estrutura do banco de dados
Acesse o cliente de terminal do seu banco de dados.

> Copie e execute os comandos que estão no arquivo `/db.sql`

### Credenciais
Abra o arquivo que sen encontra no caminho `/connection/databaseConnection.js`

E edite as seguintes linhas de acordo com suas credenciais do banco:

```js

{
    host: 'localhost',
    user: 'root',
    password: 'mariadb',
    database: 'fs06_api'
}
```

### Executar o projeto
Para executar o projeto, no diretório da aplicação através do temrinal execute:

`nodemon index.js` ou `node index.js`

Sua API estará disponível nos endereços:
- http://localhost:8000/clientes
- http://localhost:8000/veiculos
