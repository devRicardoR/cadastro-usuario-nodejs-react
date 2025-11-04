Projeto Full Stack básico – CRUD de Usuários

Este é um projeto Full Stack desenvolvido com React, Node.js, Express e Prisma ORM, que permite criar, listar, atualizar e deletar usuários.
O objetivo é demonstrar habilidades em desenvolvimento web completo, integração entre frontend e backend e boas práticas com APIs REST.

🧩 Tecnologias utilizadas
🖥️ Frontend

React

Axios

CSS / Tailwind (ou estilo utilizado)

Vite ou Create React App

⚙️ Backend

Node.js

Express

Prisma ORM

SQLite (ou outro banco configurado)

CORS

📂 Estrutura do projeto
/project-root
├── /frontend       # Aplicação React
│   ├── src/
│   ├── package.json
│   └── ...
├── /backend        # API com Express e Prisma
│   ├── prisma/
│   ├── generated/
│   ├── index.js
│   └── package.json
└── README.md
⚙️ Como rodar o projeto
1️⃣ Clonar o repositório
git clone https://github.com/devRicardoR/cadastro-usuario-nodejs-react.git
cd nome-do-repo
2️⃣ Instalar dependências

Backend:

cd backend
npm install

Frontend:

cd ../frontend
npm install
3️⃣ Configurar o banco de dados

Gerar o cliente Prisma e criar o banco local:

cd backend
npx prisma generate
npx prisma migrate dev --name init
4️⃣ Rodar o backend
npm start

O servidor iniciará em:

http://localhost:3000
5️⃣ Rodar o frontend

Em outro terminal:

cd frontend
npm run dev

A aplicação iniciará em:

http://localhost:5173

(Ou conforme indicado no terminal)

🧠 Funcionalidades principais

✅ Criar novo usuário
✅ Listar todos os usuários
✅ Atualizar informações de um usuário
✅ Deletar usuário
✅ Integração total com API REST usando Axios

💡 Exemplo de requisição POST
{
  "name": "Ricardo Cesar",
  "email": "ricardo@email.com",
  "age": 27
}
