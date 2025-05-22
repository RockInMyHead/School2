# LMS Platform

This repository contains a minimal skeleton for an online learning management system (LMS).
The architecture is split into a frontend (`Next.js`) and backend (`NestJS`) application.

## Structure

- `frontend` – Next.js 14 application
- `backend` – NestJS 10 application

Both directories include simple starter code and `package.json` files describing the
dependencies (not installed in this environment).

## Quick Start

```bash
# Frontend
cd frontend
npm install            # install packages (requires internet)
npm run dev            # start development server

# Backend
cd ../backend
npm install            # install packages (requires internet)
npm run start:dev      # start NestJS server
```

Note: This environment does not include the installed dependencies. Run `npm install`
for each application before building or running.
