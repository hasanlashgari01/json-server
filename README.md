# JSON Server API

A simple REST API built with JSON Server that provides CRUD operations for user data.

## Features

- RESTful API endpoints
- CRUD operations for user data
- Sample data with 50 users
- Each user has: id, name, avatar, year, and job information

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repository
```bash
git clone <your-repository-url>
```

2. Install dependencies
```bash
npm install
```

3. Start the server
```bash
npm start
```

The server will start on http://localhost:8000

## API Endpoints

### Users

- GET `/users` - Get all users
- GET `/users/:id` - Get a specific user
- POST `/users` - Create a new user
- PUT `/users/:id` - Update a user
- DELETE `/users/:id` - Delete a user

### Query Examples

- Filter by job: `/users?job=Frontend Developer`
- Filter by year: `/users?year=1990`

## Data Structure

```json
{
  "id": number,
  "name": string,
  "avatar": string,
  "year": number,
  "job": string
}
``` 