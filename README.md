# Video Streaming Web App

A self-hosted advanced video streaming platform built with:
- Plain HTML, CSS, JavaScript (frontend)
- Node.js, Express, SQLite (backend)

## Features

- Upload and stream your own videos
- Categories, search, comments
- User accounts and admin panel
- Responsive, modern UI

## Setup

1. Clone the repo
2. Install dependencies:
   ```bash
   cd server
   npm install express multer sqlite3
   ```
3. Start the server:
   ```bash
   node server.js
   ```
4. Visit [http://localhost:3000](http://localhost:3000)

## Customization

- Add your videos to `/public/uploads/` or use the upload feature (to be implemented).
- Adjust design in `/public/css/style.css`.
- Extend backend routes in `/server/server.js`.

## Security

- For demo purposes only! Add authentication, validation, and security checks before deploying in production.
