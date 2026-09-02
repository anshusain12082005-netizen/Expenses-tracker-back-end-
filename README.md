# Expense Tracker Backend

A beginner-friendly REST API built with Node.js, Express and MongoDB.

## Features
- Create expense
- Get all expenses
- Get single expense
- Update expense
- Delete expense
- Basic request validation
- MongoDB/Mongoose integration

## Setup

```bash
npm install
```

Create a `.env` file and add:

```env
MONGO_URI=mongodb://localhost:27017/expense_tracker
PORT=3000
```

Run:

```bash
npm start
```

For development:

```bash
npm run dev
```

## API Endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| POST | /api/expenses | Create expense |
| GET | /api/expenses | Get all expenses |
| GET | /api/expenses/:id | Get one expense |
| PUT | /api/expenses/:id | Update expense |
| DELETE | /api/expenses/:id | Delete expense |

Example POST body:

```json
{
  "title": "Lunch",
  "amount": 150,
  "category": "Food"
}
```
