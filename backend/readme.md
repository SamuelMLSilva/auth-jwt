# Nome do Projeto

Sistema de login e registro com autenticação via JWT, desenvolvido como projeto de portfólio.

## 🚀 Tecnologias

**Frontend:**

- React
- React Router
- Context API
- Vite

**Backend:**

- Node.js
- Express
- JWT (JSON Web Token)
- bcrypt

## 📋 Funcionalidades

- Registro de usuário
- Login com autenticação via JWT (cookie httpOnly)
- Persistência de sessão (mantém login após recarregar a página)
- Rotas protegidas (dashboard acessível apenas para usuários autenticados)
- Logout

## ⚙️ Como rodar o projeto localmente

### Backend

\`\`\`bash
cd backend
npm install
cp .env.example .env

# Preencha as variáveis no .env

npm run dev
\`\`\`

### Frontend

\`\`\`bash
cd frontend
npm install
cp .env.example .env

# Preencha as variáveis no .env

npm run dev
\`\`\`

## 🔑 Variáveis de ambiente

**backend/.env**
\`\`\`
PORT=
DB_USER=
DB_PASSWORD=
DB_HOST=
DB_PORT=
DB_NAME=
JWT_SECRET=
JWT_EXPIRES_IN=

# Configurações do PostgreSQL (para quando configurar o banco)

DATABASE_URL=

# URL DO FRONT

FRONTEND_URL=
\`\`\`

**frontend/.env**
\`\`\`
VITE_API_URL=
\`\`\`

## 📸 Screenshots
