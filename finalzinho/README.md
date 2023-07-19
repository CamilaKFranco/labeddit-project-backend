Labeddit Back End - Projeto de API para gerenciamento de posts

📖 Sobre o Projeto
O Labeddit é uma API que permite aos usuários criar contas, fazer login, criar posts, curtir e comentar. Além disso, o projeto serve como uma base para o desenvolvimento do front-end, que é implementado no programa. Confira o anexo para mais detalhes: clique aqui!

🔍 Principais Tópicos de Estudo
Durante o desenvolvimento deste projeto, os principais tópicos abordados incluem:

Conceitos de TypeScript.
Criação de uma API com as operações principais: get, post, put e delete.
Arquitetura em camadas para uma organização estrutural eficiente.
Programação Orientada a Objeto.
Autenticação de usuários.
STATUS: Projeto Finalizado.
🔗 Link de Acesso
Para acessar a documentação do projeto, clique aqui!.

📄 Concepção do Projeto
Para instalar as dependências necessárias, execute os seguintes comandos:

Instalando dependências
npm install

Executando o projeto
npm run dev e npm run start.

🚀 Funcionalidades
A API oferece as seguintes funcionalidades:

Requisições disponíveis:
SignUp: Criação de um usuário na API usando o método post.
Login: Autenticação do usuário na API usando o método post.
GetPosts: Recuperação de todos os posts da API, mas apenas com o token obtido após o login ou signup, utilizando o método get.
GetPostById: Recuperação de um post específico pelo seu ID, mas apenas com o token obtido após o login ou signup, utilizando o método get.
CreatePost: Criação de um novo post na API, mas apenas com o token obtido após o login ou signup, utilizando o método post.
CreateComment: Criação de um novo comentário na API, mas apenas com o token obtido após o login ou signup, utilizando o método post.
LikeOrDislikePost: Funcionalidade de curtir ou descurtir um post na API, utilizando o token adquirido após o login ou signup, bem como o ID do post. É necessário enviar um valor booleano (true para like e false para dislike) no corpo da requisição.
LikeOrDislikeComment: Funcionalidade de curtir ou descurtir um comentário na API, utilizando o token adquirido após o login ou signup, bem como o ID do comentário. É necessário enviar um valor booleano (true para like e false para dislike) no corpo da requisição.
📚 Bibliotecas Utilizadas
O projeto utiliza as seguintes bibliotecas:

Dependências:
bcryptjs,
cors,
dotenv,
express,
jsonwebtoken,
knex,
sqlite3,
uuid,
zod

Dependências de Desenvolvimento:
@types/bcryptjs,
@types/cors,
@types/express,
@types/jsonwebtoken,
@types/knex,
@types/node,
@types/uuid,
ts-node-dev,
typescript

💡 Programas Utilizados
Durante o desenvolvimento, foram utilizados os seguintes programas:

VSCode
PostMan

https://bold-crescent-312211.postman.co/documentation/24823280-8e53a808-0ffe-48f5-a4d2-560cd2deaf7e/publish?workspaceId=b3a0e98e-4d17-45d4-92ee-64b1c2445d01

💻 Tecnologias Empregadas
As principais tecnologias utilizadas no projeto são:

Typescript
Express
Git


