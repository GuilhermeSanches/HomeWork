# post-nodejs-mysql


Para testar a aplicação, baixe o repositório:
```
git clone https://github.com/nicholasess/post-nodejs-mysql
```
Instale as dependências:
```
npm install
```
Importe o arquivo lembrete.sql no seu banco de dados.

E rode o projeto:
```
node bin/www
```

As rotas são essas:
```
GET /lembretes -> todos os lembretes
POST /lembretes -> cadastra os lembretes

GET /lembrete/:id -> retorna o perfil do lembrete através do id
PUT /lembrete/:id -> atualiza o lembrete através do id
DELETE /lembrete/:id -> exclui o lembrete através do id
```
