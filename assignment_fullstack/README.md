# Backend Developer Assignment

## 🚀 Features
- REST API with authentication & role-based access
- CRUD for tasks
- Secure password hashing (bcrypt) + JWT
- MongoDB integration with Mongoose
- React + Tailwind frontend

## 📦 Setup
1. Clone repo
2. Copy `.env.example` to `.env` and update values
3. Install backend deps:
   ```bash
   npm install
   npm run dev
   ```
4. Setup frontend:
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

## 🔑 API Endpoints
- `POST /api/v1/auth/register`
- `POST /api/v1/auth/login`
- `GET /api/v1/tasks` (JWT required)
- `POST /api/v1/tasks`
- `PUT /api/v1/tasks/:id`
- `DELETE /api/v1/tasks/:id`

