
# Backend Development Assignment

A REST API built using Node.js, Express.js,
MongoDB Atlas and Mongoose.

## Features
- Create product (POST)
- Read products (GET)
- Update product (PUT)
- Delete product (DELETE)

## Technologies
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Postman

## Installation
1. Clone this repository.
2. Open the project in VS Code.
3. Run `npm install`.
4. Create a `.env` file based on `.env.example`.
5. Add your MongoDB Atlas connection string.
6. Run `npm run dev`.

## API Endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| POST | /api/products | Create product |
| GET | /api/products | Read products |
| GET | /api/products/:id | Read one |
| PUT | /api/products/:id | Update product |
| DELETE | /api/products/:id | Delete product |

## Testing
All CRUD operations were tested successfully
using Postman.
