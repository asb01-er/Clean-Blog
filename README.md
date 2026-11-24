# Clean Blog

A server-rendered blogging application built with Node.js. Users can register, log in and manage articles with full create, read, update and delete (CRUD) workflows.

**Live demo:** https://clean-blog-0j27.onrender.com
**Code:** https://github.com/asb01-er/Clean-Blog

> The demo runs on a free Render server, so the first load can take up to 30 seconds.

## Features

- User registration and login
- Create, read, update and delete articles
- Server-rendered pages
- Clean, responsive blog layout

## Tech stack

- Node.js
- Server-rendered web pages
- HTML and CSS

## Getting started

### Prerequisites

- Node.js 18+
- The database your app connects to (see the environment variables below)

### Setup

```bash
git clone https://github.com/asb01-er/Clean-Blog.git
cd Clean-Blog
npm install
```

Create a `.env` file in the project root with the connection string and secrets your app reads, for example:

```env
PORT=3000
DATABASE_URL=your_database_connection_string
SESSION_SECRET=your_secret
```

Start the app:

```bash
npm start
```

Open http://localhost:3000.

## Deployment

Deployed on Render as a Node web service with `npm install` as the build command and `npm start` as the start command. Add the same environment variables in Render's Environment tab.

## Author

**Ernest Ekelem** — [GitHub](https://github.com/asb01-er) · [LinkedIn](https://www.linkedin.com/in/ernest-ekelem-5a771735a)
