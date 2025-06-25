# Appointment Booking System API

## 📦 Tech Stack
- **Framework**: NestJS
- **Language**: TypeScript
- **Database**: PostgreSQL (via TypeORM)
- **Validation**: class-validator
- **Config**: @nestjs/config
- **Optional**: Swagger, Jest, Schedule

## 🚀 Setup Instructions
```bash
git clone <repo-url>
cd appointment-booking-system
npm install
cp .env.example .env
npm run start:dev
```

## 🛠 Migration or Schema
Use TypeORM CLI or sync for schema generation.

## 🔌 API Endpoints (Sample)
- POST `/users` → Register user
- GET `/users` → List users
- POST `/services` → Create service
- GET `/services` → List services
- POST `/appointments` → Book appointment
- GET `/appointments` → List appointments
- PUT `/appointments/:id/cancel` → Cancel
- PUT `/appointments/:id/complete` → Complete

## 🧪 Sample cURL
```bash
curl -X POST http://localhost:3000/users -H "Content-Type: application/json" -d '{"name":"John","email":"john@example.com"}'
```

## 📁 Folder Structure
```
src/
├── users/
├── services/
├── appointments/
├── common/
```

