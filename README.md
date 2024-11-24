# 🚀 **To-Do App Setup Guide**

This repository contains both the **React frontend** and **Nest.js backend** projects. Follow the instructions below to set up the application locally or using Docker containers.

## 📂 **Project Structure**

todo-app/
│
├── react-todo/       # React frontend
└── nest-todo/        # Nest.js backend


---

 # Clone the Repository:
First, clone the repository to your local machine:
```bash
git clone https://github.com/your-username/todo-app.git
cd todo-app
git submodule update --init --recursive
```

## 🛠️ **Local Installation:**



### **1. Install Dependencies:**

#### **Frontend (React):**
Navigate to the `react-todo` directory and install dependencies:

```bash
cd react-todo
npm install
```

#### **Backend (Nest.js):**
Navigate to the `nest-todo` directory and install dependencies:

```bash
cd react-todo
npm install
```
### **2. Run the Projects Locally:**

#### **Start the Backend (Nest.js):**
Start the backend server:

```bash
cd nest-todo
npm run start:dev  # The backend will run on http://localhost:3000
```

#### **Start the Frontend (React):**
Start the frontend application:

```bash
cd ../react-todo
npm run dev  # The frontend will run on http://localhost:5173
```

## 🐋 **Docker Installation:**

#### **1. Prerequisites:**
Ensure you have Docker and Docker Compose installed on your machine. You can download them from:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

#### **2. Run with Docker Compose:**
In the root directory of the project (`todo-app`), run the following command to build and start both containers:

```bash
docker-compose up --build
```
### **3. Access the Application:**

#### **Frontend (React):**
Open your browser and go to [http://localhost:5173](http://localhost:5173).

#### **Backend (Nest.js):**
Open your browser and go to [http://localhost:3000](http://localhost:3000).
