# Redeploy trigger

Timestamp: 2026-08-17T15:22:00Z

Project should build with root `vercel.json`:
- install: yarn install --cwd frontend
- build: yarn --cwd frontend build
- output: frontend/build

Dashboard must use Framework **Other** or **Create React App**, not Python.
Root Directory: `frontend` (preferred) or `.` with root vercel.json.
