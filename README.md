# TS - Fastify - Mongoose Boilerplate

TypeScript + Fastify + Mongoose backend service.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Set environment variables (development):
Create a file named `development.env` in the project root with your development environment variables. For example:

```
DB_URL=mongodb://localhost:27017,localhost:27018,localhost:27019/[db-name]
```

Adjust values as needed for your local setup.


3. Run in development:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
npm start
```

