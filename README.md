## Markdown-Notes-Taker
#### A full-stack Web Application for taking notes in Markdown with live preview, grammar checking, and persistent storage.

## Features of the Application:
---
### 1. Markdown to HTML Render:
--> Used [marked](https://www.npmjs.com/package/marked) npm package for parsing markdown text to HTML in real time

### 2. Grammar Check Feature:
--> Integrated [LanguageTool](https://dev.languagetool.org/public-http-api) public API for grammar and spelling validation

### 3. Word Pattern Search within the Note:
--> Implemented KMP (Knuth-Morris-Pratt) algorithm for efficient pattern matching inside notes

### 4. Markdown File Upload Feature:
--> Used [multer](https://www.npmjs.com/package/multer) npm package for handling markdown file uploads

### 5. RESTful API Endpoints:
--> Full CRUD support — Create, Read, Update and Delete notes via REST API

---
## Tech Stack:
1. HTML, CSS, JavaScript — Frontend
2. Node.js, Express.js — Backend
3. PostgreSQL — Database
4. EJS — Templating Engine

---
## Steps to Run the Application:
1. Clone the repository
2. cd into the project folder
3. Create a `.env` file with your PostgreSQL credentials:
DB_USER=your_postgres_username
DB_HOST=localhost
DB_NAME=your_database_name
DB_PASSWORD=your_password
DB_PORT=5432
4. Run `npm install`
5. Run `node index.js`
6. Open browser at `http://localhost:3000`

---
## Live Demo:
http://54.161.108.225/