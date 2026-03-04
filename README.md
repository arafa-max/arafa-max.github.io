# FX — Todo List & Task Manager

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=flat-square&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-latest-green?style=flat-square&logo=fastapi)
![JWT](https://img.shields.io/badge/JWT-Auth-orange?style=flat-square)
![Railway](https://img.shields.io/badge/Deployed-Railway-purple?style=flat-square)

A full-featured task management REST API with JWT authentication and admin panel.

🔗 **Live Demo:** [fx.up.railway.app](https://fx.up.railway.app/)
📖 **API Docs:** [fx.up.railway.app/docs](https://fx.up.railway.app/docs)

---

## Features

- ✅ JWT Authentication (register, login, refresh tokens)
- ✅ Full CRUD for tasks (create, read, update, delete)
- ✅ Admin panel with user management
- ✅ Password hashing with bcrypt
- ✅ Auto-generated Swagger API documentation
- ✅ Deployed on Railway

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Python 3.9+ |
| Framework | FastAPI |
| Auth | JWT (JSON Web Tokens) |
| Security | bcrypt |
| Docs | Swagger / OpenAPI |
| Deploy | Railway |

---

## API Endpoints

### Auth
```
POST /auth/register   — Register new user
POST /auth/login      — Login & get JWT token
POST /auth/refresh    — Refresh access token
```

### Tasks
```
GET    /tasks         — Get all tasks
POST   /tasks         — Create new task
PUT    /tasks/{id}    — Update task
DELETE /tasks/{id}    — Delete task
```

### Admin
```
GET    /admin/users   — Get all users
DELETE /admin/users/{id} — Delete user
```

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/arafa-max/fx

# Install dependencies
pip install -r requirements.txt

# Run the server
uvicorn main:app --reload
```

Open [http://localhost:8000/docs](http://localhost:8000/docs) to see the API docs.

---

## Author

**Arafat** — Full-Stack Web Developer
- GitHub: [@arafa-max](https://github.com/arafa-max)
- Portfolio: [arafa-max.github.io](https://arafa-max.github.io)
