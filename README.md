<p align="center">
<img src="./public/img/logo.png" alt="Logo Doe Sangue"></img>
</p>

<h3 align = "center"> Doe Sangue - MaratonaDev 3.0</h3>

## :computer: O projeto

<p>O proejto Doe Sangue é uma sistema para cadastro de doadores de sangue, onde serão armazenados dados (nome, email, tipo sanguíneo) 
desses doadores em um banco de dados.</P>

## :rocket: Tecnologias

Durante o desenvolvimento desse projeto foram utilizadas as seguintes tecnoligias:


- [Html](https://tableless.com.br/o-que-html-basico/)
- [CSS](https://www.w3schools.com/css/)
- [Javascript](https://developer.mozilla.org/pt-BR/docs/Aprender/JavaScript)
- [Node.js](https://nodejs.org/en/)
- [Nodemon](https://nodemon.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Nunjucks](https://mozilla.github.io/nunjucks/)

## :elephant: Banco de Dados

Para armazenar os dados dos doadores utilizamos o PostgreSQL, onde criamos o banco chamado **'doe'**, com a tabela chamada **'donors'**.
Segue o código SQL para criar a tabela:
```
CREATE TABLE "public"."donors" (
"id" int4 DEFAULT nextval('donors_id_seq'::regclass) NOT NULL,
"name" text COLLATE "default" NOT NULL,
"email" text COLLATE "default" NOT NULL,
"blood" text COLLATE "default" NOT NULL
)
WITH (OIDS=FALSE);
```
## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](/LICENSE) para mais detalhes.

---




