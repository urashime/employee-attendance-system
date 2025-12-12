
# Employee Attendance System

**Fullstack demo (React + Express + MongoDB)**

Features:
- Frontend: Vite + React, TailwindCSS, Framer Motion animations, clean UI cards and tables
- Backend: Express + Mongoose (MongoDB). Endpoints for login, check-in, check-out, attendance listing.
- Roles: `admin` and `employee`. Admin can view all attendance; employees can check-in / check-out and see their records.
- Light/Dark theme switch.
- Ready-to-run demo. For production, add secure auth, validation, and HTTPS.

## Quick start (locally)

Requirements:
- Node.js 18+
- npm
- MongoDB instance (local or cloud). For local, default `mongodb://127.0.0.1:27017/attendance_demo`

1. Unzip the package and open terminal.

2. Start backend:
```bash
cd backend
npm install
# create .env file (example at .env.example) or set MONGODB_URI
cp .env.example .env
# edit .env if needed, then:
npm run dev
```

3. Start frontend (in a separate terminal):
```bash
cd frontend
npm install
npm run dev
```

4. Open browser at `http://localhost:5173`

## Default demo users
- Admin: `admin1` / `password` (role: admin)
- Employee: `emp1` / `password` (role: employee)
You can create new users via MongoDB or add a registration endpoint.

## Notes
- This is a demo to showcase structure, UI and working endpoints.
- Replace secrets and hard-coded items before production.

