# My API

Express API for the UserFlow dashboard.

## Features

- `GET /users` - list all users
- `POST /users` - add a user
- `DELETE /users/:id` - delete a user

## Setup

```bash
cd "c:\Users\Admin\Desktop\my-api"
npm install
cp .env.example .env
```

Then edit `.env` with your PostgreSQL credentials.

## Run

```bash
node server.js
```

The API listens on `http://localhost:5000`.

## Database

The backend uses PostgreSQL and `pg` to connect with these environment variables:

- `PGUSER`
- `PGHOST`
- `PGDATABASE`
- `PGPASSWORD`
- `PGPORT`

## License

MIT
