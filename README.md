# Reddit

Full stack reddit clone built with React, Redux, Node.js, Express, and PostgreSQL.

## Features
- JWT authentication
- Create, update, and delete posts and comments
- Upvote/downvote posts and comments
- Nested comments threading
- Home page feed (front page)
- Subreddit specific feed
- Create subreddits

## Installation

1. Install backend dependencies

```
cd backend
npm install
```

2. Install frontend dependencies

```
cd frontend
npm install
```


3. Create a postgres database named 'reddit'

4. Run the database migrations

```
cd backend
npm run db-migrate-dev up
```

## Usage
1. Start server

```
cd backend
npm run dev
```

2. Start client
```
cd frontend
npm start
```