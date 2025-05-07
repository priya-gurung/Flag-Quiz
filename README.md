# 🌍 World Flags Quiz App

This is a Node.js application that connects to a PostgreSQL database and fetches data from a `flags` table. It can be used as a base for a world capital or flags quiz game.

---

## Features

- Connects to PostgreSQL using `pg` module
- Reads environment variables from `.env`
- Fetches flag data from database
- Express server setup
- Structured for expansion (e.g., adding frontend, routes, APIs)

---


---

## Setup Instructions

1. **Clone the repo**  
   ```bash
   git clone https://github.com/priya-gurung/Flag-Quiz
   cd Flag_Quiz
   npm install

2. **Create a .env file**
   ```bash
   DB_USER=your_db_user
   DB_HOST=localhost
   DB_NAME=your_db_name
   DB_PASSWORD=your_db_password
   DB_PORT=5432

3. **Run the app**
   ```bash
   nodemon index.js


