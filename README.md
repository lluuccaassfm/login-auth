# Login Autenticação

Projeto com implementação de autenticação JWT. 

## login-auth-api (backend)
Utiliza **Java 17** com **Spring Boot**

Utiliza bando em memória **(h2database)**

Possui 3 rotas implementadas:
- /auth/register -> efetua o registro de um usuário
- /auth/login -> efetua o login de um usuário, retornando um token JWT
- /user -> rota autenticada para validar o uso do token, pois só funciona com um token válido

## login-page (frontend)
Utiliza **Angular 17**

Possui 3 rotas implementadas: 
- /signup -> para fazer o registro de um usuário
- /login -> para fazer o login de um usuário
- /user -> rota autenticada, somente acessada em uma sessão authenticada

Comando para instalar as dependências do _login-page_: 
> npm install

Comando para iniciar o _login-page_: 
> npm start
