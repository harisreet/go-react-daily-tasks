# Daily Tasks

**Daily Tasks** is a full-stack task management application built with a Go backend and a React + TypeScript frontend. It helps users efficiently manage tasks with a modern, responsive UI.

---

## 🚀 Features

- 📝 Full CRUD functionality: Create, Read, Update, and Delete tasks effortlessly  
- ✅ Mark tasks as completed to track progress easily  
- ⚡ Fast and lightweight backend built with Go for high performance  
- 🎨 Modern, responsive frontend built with React, TypeScript, and Chakra UI for clean and accessible UI components  
- 💾 Data persistence with MongoDB, a scalable NoSQL database  

---

## 🛠️ Tech Stack

- **Go** — Backend API  
- **React + TypeScript** — Frontend UI  
- **Chakra UI** — UI components  
- **MongoDB** — Database  
- **React Query** — Data fetching & caching  
- **Vite** — Frontend build tool  

---

## 🏁 Getting Started (Local Setup)

### Prerequisites

- Go v1.18+  
- Node.js v16+  
- Git  
- MongoDB (Atlas or local)

### Steps

1. **Clone the repository**  
```bash
git clone https://github.com/harisreet/react-go-todolist
cd react-go-todolist
```
2. **Configure environment variables:**

    Create a `.env` file in the project root (example):
    ```ini
    PORT=5000
    MONGODB_URI="your-mongodb-atlas-connection-uri"
    ENV=DEVELOPMENT
    ```
3. **Start Backend API server:**
   ```bash
     cd go-and-react
     go run main.go
     ```
4. **Start Frontend server:**
    ```bash
    cd client
    npm install
    npm run dev
    ```
5. **Access the app:**
    - Application : [http://localhost:5173](http://localhost:5173)  

### Demo Video : [demo](https://drive.google.com/file/d/1IyeSZBOPwyTGARuYmNMFj26Fd6ABIoOb/view?usp=drive_link) 

