# APIRESTFULL 
Siga as inntruções e tudo vai dar certo!!


# 1. Codigos a serem digitados no terminal do VSCODE

mkdir api-rest-system
cd api-rest-system

# 2. Inicializar o projeto com npm:
npm init -y

# 3. Instalar as dependências:
npm install express mongoose swagger-ui-express body-parser dotenv

# 4. Instalar ferramentas de desenvolvimento:
npm install nodemon --save-dev

# 5. Editar o arquivo package.json para adicionar scripts: Adicione o seguinte em "scripts":
"scripts": {
  "start": "node server.js",
  "dev": "nodemon server.js"
}

# ASSIM QUE TUDO TIVER INSTALADO, E VOCÊ JA TIVER INSERIDO SUA KEY DA MONGODB, É SÓ INICIALIZAR USANDO O SEGUINTE COMANDO:
npm run dev


Acessar a API:

Rotas da API: http://localhost:5000/api/users
Documentação Swagger: http://localhost:5000/api-docs
