# Week 3 - Backend Projects

This folder contains two backend demo projects built during Week 3 of the MERN training.

## Projects

### 1. Backend_demo

- Location: `week-3/Backend_demo`
- Description: A simple Express + Mongoose backend demo.
- Main file: `server.js`
- Package manager: npm
- Dependencies: `express`, `mongoose`

#### How to run

```bash
cd week-3/Backend_demo
npm install
node server.js
```

> This project uses ESM modules (`type: module`).

### 2. BACKEND-DEMO-2

- Location: `week-3/BACKEND-DEMO-2`
- Description: A more advanced backend demo with authentication-related packages and product APIs.
- Main file: `server.js`
- Package manager: npm
- Dependencies: `bcryptjs`, `cookie-parser`, `cors`, `dotenv`, `express`, `jsonwebtoken`, `mongoose`
- Dev dependency: `nodemon`

#### API endpoints

- `POST /products`
- `GET /products`
- `GET /products/<pid>`
- `PUT /products/<pid>`

#### How to run

```bash
cd week-3/BACKEND-DEMO-2
npm install
npm run start # or node server.js
```

> Make sure to add a `.env` file if the project requires environment variables.

## Notes

- `BACKEND-DEMO-2` already contains its own `README.md` with project-specific API details.
- Use separate terminals for each demo if you want to run both at the same time.
