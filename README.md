# 🌍 Travel Tracker -- Visited Countries App

A simple full-stack web application built using **Node.js, Express,
PostgreSQL, and EJS** that allows multiple users to track the countries
they have visited.

## 🚀 Tech Stack

-   Node.js
-   Express.js
-   PostgreSQL
-   EJS
-   CSS

## 📂 Project Structure

    travel-tracker/
    │
    ├── public/
    │   ├── main.css
    │   └── new.css
    │
    ├── views/
    │   ├── index.ejs
    │   └── new.ejs
    │
    ├── index.js
    ├── package.json
    ├── package-lock.json
    └── README.md

## ⚙️ Installation

1.  Clone the repository

```{=html}
<!-- -->
```
    git clone https://github.com/your-username/travel-tracker.git
    cd travel-tracker

2.  Install dependencies

```{=html}
<!-- -->
```
    npm install

## 🗄️ Database Setup

1.  Create database:

```{=html}
<!-- -->
```
    CREATE DATABASE visited_countries;

2.  Run the queries inside `queries.sql` in pgAdmin or PostgreSQL
    terminal.

## 🔑 Configure Database Connection

Open `index.js` and update:

``` js
const db = new pg.Client({
  user: "postgres",
  host: "localhost",
  database: "visited_countries",
  password: "your_password",
  port: 5432,
});
```

## ▶️ Run the App

    node index.js

Open in browser:

    http://localhost:3000

## ✨ Features

-   Multi-user support
-   Add visited countries
-   Duplicate entry protection
-   Error handling
-   Simple UI

## 👨‍💻 Author

Ajay
