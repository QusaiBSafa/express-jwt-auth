# Infrastructure Overview
A simple Express application with JWT authentication.

## Data Models
- User: `{ id: number, username: string, password: string }`

## API Design
- POST `/api/register`: Register a new user
- POST `/api/login`: Authenticate user and return JWT

## Key Decisions
- Using JWT for stateless authentication
- Storing passwords securely using hashing