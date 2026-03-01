# Localhost Server Setup

## 📌 Project Description

This project is a simple server application built using JavaScript. The server runs on **localhost** and listens on a defined port (**8000**). When accessed through a web browser, it returns a plain text response.

When a request is received, the server responds with:

```
Hello From Server
```

---

## 🛠 Programming Language Used

- JavaScript

---

## 📚 Runtime / Library Used

- Node.js (JavaScript runtime environment)
- Built-in `http` module (no external frameworks used)

This project does not use any external frameworks like Express. It uses Node.js’s native `http` module to create and run the server.

---

## 🚀 Steps to Run the Server Locally

### 1️⃣ Install Node.js

Download and install the LTS (Long Term Support) version of Node.js from the official website.

After installation, verify it by running the following command in your terminal or command prompt:

```
node -v
```

If a version number appears, Node.js is installed correctly.

---

### 2️⃣ Create Project File

Create a file named:

```
index.js
```

Paste the provided server code into this file.

---

### 3️⃣ Run the Server

Open a terminal in the project folder and run:

```
node index.js
```

If successful, you will see:

```
Server Started!
```

---

### 4️⃣ Test the Server

Open your web browser and navigate to:

```
http://localhost:8000
```

You should see the response:

```
Hello From Server
```

---

## ✅ Requirements Fulfilled

- Server runs on localhost
- Server listens on a defined port (8000)
- At least one working route is implemented
- Returns a plain text response
- Application runs without errors

---

## 📂 Project Structure

```
project-folder/
│
└── index.js
```

---
