# My API

Express API for the UserFlow dashboard.

## Features

- `GET /users` - list all users
- `POST /users` - add a user
- `DELETE /users/:id` - delete a user

## Setup

```bash
cd c:\Users\Admin\Desktop\my-api
npm install
```

No database setup needed — the app uses SQLite automatically.

## Run

```bash
node server.js
```

The API listens on `http://localhost:5000`.

## Database

The backend uses **SQLite** for data storage. The database file (`users.db`) is created automatically on first run and stored locally.

No environment variables or external database setup required.

## License

MIT
