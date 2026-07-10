# express-jwt-auth

## Description
A simple Express API implementing JWT authentication with login and register endpoints.

## What's Built
- User registration and login
- JWT token generation and validation

## How to Run
1. Clone the repository
2. Navigate to the project directory
3. Run `npm install` to install dependencies
4. Create a `.env` file with your environment variables
5. Run `npm start` to start the server

## API Documentation
### Register
- **Endpoint:** POST `/api/register`
- **Body:** `{ "username": "string", "password": "string" }`
- **Response:** `{ "token": "string" }`

### Login
- **Endpoint:** POST `/api/login`
- **Body:** `{ "username": "string", "password": "string" }`
- **Response:** `{ "token": "string" }`

## Environment Variables
- `JWT_SECRET`: Secret key for JWT signing
- `PORT`: Port for the server (default: 3000)