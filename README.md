<h1 align = "center"> Find Your Geek </h1>

### APRESENTAÇÃO

<p align = "center"> Esse é o projeto final do Bootcamp de Desenvolvimento BackEnd. Consiste em um app que tem por objetivo unir pessoas com gostos semelhantes do mundo Geek, o Find Your Geek contará com as seguintes funções:

O seu cadastro;

Deixa-lo disponível para pessoas que tenham interesses em comum com os seus;

Consultar os Geeks cadastrados com informações como:

_Nome;_
_Email;_
_Cidade onde reside;_
_Tipo de jogo que o interessa;_
_Descrição._

Além disso, poderá filtrar os jogadores pela cidade e tipo de jogo que o interessa.

Favoritar seus usários preferidos

</p>

#### API - ROUTES

## GET

- [x] Listar todos os usuários:
<p align = "center"> [https://find-your-geek.herokuapp.com/findyourgeek/all] </p>

## POST

- [x] Cadastrar o usuário:
<p align = "center"> [https://find-your-geek.herokuapp.com/findyourgeek/id]

O cadastro deve ser feito no seguinte formato:

```json
{
  "name": " ",
  "email": " ",
  "password": " ",
  "city": " ",
  "type": " ",
  "descricao": " "
}
```

## GET

- [x] Filtrar os usuários pelo id:
<p align = "center"> [https://find-your-geek.herokuapp.com/findyourgeek/id]
</p>

## GET

- [x] Filtrar usuários por cidade:
<p align = "center"> [https://find-your-geek.herokuapp.com/findyourgeek/city] 
</p>

## GET

- [x] Filtrar usuários por tipo de jogo:

<p align = "center"> [https://find-your-geek.herokuapp.com/findyourgeek/type] </p>

## POST

- [x] Favoritar usuários:

<p align = "center"> [https://find-your-geek.herokuapp.com/findyourgeek/favorite/id] </p>

## ROTA PARA FAZER LOGIN

## POST

- [x] Fazer o login:

<p align = "center"> [https://find-your-geek.herokuapp.com/fyg/login] 
</p>

## Essas rotas só funcionarão após o login

## PATCH

- [x] Editar tipo de jogo preferido do usuário:

<p align = "center"> [https://find-your-geek.herokuapp.com/findyourgeek/updateType/id] 
</p>

## PATCH

- [x] Editar descrição do usuário:

<p align = "center"> [https://find-your-geek.herokuapp.com/findyourgeek/updateDesc/id] 
</p>

## PATCH

- [x] Editar cidade do usuário:

<p align = "center"> [https://find-your-geek.herokuapp.com/findyourgeek/updateCity/id]  
</p>

## DELETE

- [x] Excluir usuário

<p align = "center"> [http://find-your-geek.herokuapp.com/findyourgeek/delete/id] 
</p>

## POST

- [x] Favoritar usuário:

<p align = "center"> [http://find-your-geek.herokuapp.com/findyourgeek/favorite/id] 
</p>

## Contato

**Linkedin**: [https://www.linkedin.com/in/melg88]

**Email**: [meduardalima88@gmail.com]

## Linguagemn utilizada no Desenvolvimento

- [x] JavaScript
- [x] Node.js

## Banco de Dados

- [x] MongoDB

## Dependências

- [x] Express
- [x] Nodemon
- [x] Mongoose
- [x] Yup
- [x] Bcrypt

## Hospedagem

- [x] Heroku
