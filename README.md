# Around The U.S. - Backend

## Overview

Backend API built with Node.js and Express for the Around The U.S. project.
This version uses local JSON files as a temporary data source.

## Features

- Get all users
- Get user by ID
- Get all cards
- 404 error handling

## Tech Stack

- Node.js
- Express
- ESLint (Airbnb)

## Run the Project

```bash
npm install
npm run start
```

Server runs on:

```text
http://localhost:3000
```

## Endpoints

```http
GET /users
GET /users/:id
GET /cards
```

## Structure

```text
routes/   - API routes
data/     - JSON data
app.js    - entry point
```

## Lint

```bash
npm run lint
```

## Author

Charles Rocha Marques
