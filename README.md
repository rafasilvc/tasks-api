# Tasks API — Backend

API REST para gerenciamento de tarefas, desenvolvida com Node.js, Express e MongoDB.

## Tecnologias

- Node.js
- Express
- MongoDB Atlas + Mongoose
- dotenv / cors

## Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/rafasilvc/tasks-api.git
cd tasks-api
```

### 2. Instale as dependências

```bash
npm install
```

### 3. Configure as variáveis de ambiente

Copie o arquivo `.env.example` para `.env`:

```bash
cp .env.example .env
```

Preencha com sua URI do MongoDB Atlas:

MONGO_URI=mongodb+srv://usuario:senha@cluster.mongodb.net/tasksdb
PORT=3000

### 4. Inicie o servidor

```bash
npm run dev
```

## Endpoints

| Método | Rota           | Descrição               |
|--------|----------------|-------------------------|
| GET    | /api/tasks     | Listar todas as tarefas |
| GET    | /api/tasks/:id | Buscar tarefa por ID    |
| POST   | /api/tasks     | Criar nova tarefa       |
| PUT    | /api/tasks/:id | Atualizar tarefa        |
| DELETE | /api/tasks/:id | Deletar tarefa          |

## Deploy

> https://tasks-api-hb7h.onrender.com
