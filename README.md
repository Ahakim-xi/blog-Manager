# 📝 Blog Manager App

A simple frontend **Blog Manager** app that allows users to view, add, edit, and delete blog posts using a mock REST API powered by [JSON Server](https://github.com/typicode/json-server).

---

## 🚀 Features

- ✅ Fetch and display blog post titles from a mock API  
- 🔍 Click a title to view full post details (title, author, content)  
- ➕ Add a new blog post using a form  
- 📝 Edit post content using an editable form  
- ❌ Delete posts  
- 🔁 All changes persist to the JSON backend (mock API)

---

## 🎯 Learning Goals

- Access data from an API using `GET` requests and update the DOM  
- Listen for user events and update the DOM in response  
- (Advanced) Send data using `POST`, `PATCH`, and `DELETE` requests

---

## 🛠 Technologies Used

- HTML5  
- CSS  
- JavaScript  
- [JSON Server](https://github.com/typicode/json-server)

---

## 📁 Project Structure

```
project-folder/
├── index.html       # Main HTML file  
├── styles.css       # Stylesheet  
├── script.js        # JavaScript logic  
├── db.json          # Mock backend data (JSON Server)  
└── README.md        # You're reading this file!
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Ivy-chemutai/Blog-Post-Manager.git
cd blog-manager
```

### 2. Install and Start JSON Server

Make sure you have **Node.js** installed. Then run:

```bash
npm install -g json-server@0.17.4
npx json-server --watch db.json
```

> The backend will be available at:  
> 🔗 `http://localhost:3000/posts`

### 3. Run the Frontend

Use **Live Server** (VS Code extension) or manually open `index.html` in your browser.

---

## 🎬 Demo Preview

The Blog Manager App allows you to:

- 📃 Load and display blog post titles  
- 🔍 View full blog post details on click  
- ➕ Add a new post  
- ✏️ Edit an existing post  
- ❌ Delete a post

---

## 📡 API Endpoints

| Method | Endpoint         | Description                  |
|--------|------------------|------------------------------|
| GET    | `/posts`         | Fetch all blog posts         |
| GET    | `/posts/:id`     | Fetch a specific blog post   |
| POST   | `/posts`         | Create a new blog post       |
| PATCH  | `/posts/:id`     | Update an existing blog post |
| DELETE | `/posts/:id`     | Delete a blog post           |

---

## 👤 Author

**Abdihakim Ali**

---

## 📃 License

This project is for educational purposes only.

---
