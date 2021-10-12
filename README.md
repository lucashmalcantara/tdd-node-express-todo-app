# tdd-node-express-todo-app

Este repositório foi desenvolvido com base no vídeo [NodeJS Express Test-Driven API Development (TDD)](https://www.youtube.com/watch?v=M44umyYPiuo&list=WL).

# Configuração do Ambiente

1 - Executar para criar o projeto: `npx express-generator --no-view api-tdd` em seguida `npm i`

2 - Intalar o jest e [supertest](https://github.com/visionmedia/supertest) no ambiente de DEV: `npm install -D jest supertest`

2 - Instalar [http-errors](https://github.com/jshttp/http-errors) para facilitar o retorno de erros com express: `npm install http-errors  `

# Informações do projeto

- Foi adicionada o script `"test": "jest --watchAll"` na seção scripts do `package.json` para sempre executar os testes quando alguma alteração for feita no código. É interessante usar essa configuração quando estiver usando TDD, para que os testes executem lado a lado com o desenvolvimento do código.

