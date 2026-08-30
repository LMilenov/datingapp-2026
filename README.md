# Dating App 💕

A full-stack dating application built with **ASP.NET Core** and **Angular**.

🌐 **Live Demo:**  
https://da-26-eeemcqgse6dja8dp.swedencentral-01.azurewebsites.net/

---

## 📌 About the Project

Dating App is a full-stack web application where users can create profiles, upload photos, browse other members, like users, and communicate through real-time messaging.

The project was built as part of a full-stack development course and demonstrates modern web development concepts including authentication, authorization, real-time communication, image management, and deployment.

---

## ✨ Features

### 👤 User Features

- User registration and login
- JWT authentication
- User profiles
- Edit profile information
- Browse members
- Filter members by gender and age
- Upload and manage photos
- Set a main profile photo
- Like other members
- View received and sent likes
- Real-time messaging with SignalR
- Online user presence
- Message read status

### 🛡️ Administration & Moderation

- Role-based authorization
- Admin role management
- Moderator functionality
- Photo moderation
- Photo approval system

---

## 🛠️ Technologies Used

### Backend

- C#
- ASP.NET Core
- .NET 10
- Entity Framework Core
- ASP.NET Identity
- SQL Server
- JWT Authentication
- SignalR
- Cloudinary

### Frontend

- Angular
- TypeScript
- HTML
- CSS
- Tailwind CSS
- DaisyUI

### Deployment & Tools

- Docker
- Azure App Service
- Git & GitHub
- Postman

---

## 🏗️ Project Structure

```text
datingapp-2026
│
├── API/                # ASP.NET Core Web API
├── client/             # Angular frontend
├── docker-compose.yml  # SQL Server Docker configuration
└── DatingApp.slnx
```

---

## 🚀 Running the Project Locally

### Prerequisites

Make sure you have installed:

- .NET 10 SDK
- Node.js
- Angular CLI
- Docker Desktop

### 1. Clone the repository

```bash
git clone https://github.com/LMilenov/datingapp-2026.git
cd datingapp-2026
```

### 2. Start SQL Server with Docker

```bash
docker compose up -d
```

### 3. Run the Backend

Navigate to the API folder:

```bash
cd API
```

Restore dependencies:

```bash
dotnet restore
```

Apply migrations:

```bash
dotnet ef database update
```

Run the API:

```bash
dotnet run
```

### 4. Run the Angular Client

Open another terminal and navigate to the client folder:

```bash
cd client
```

Install dependencies:

```bash
npm install
```

Start the application:

```bash
npm start
```

The Angular application will run at:

```text
https://localhost:4200
```

---

## 🌐 Live Application

🚀 **Try the application here:**

https://da-26-eeemcqgse6dja8dp.swedencentral-01.azurewebsites.net/

---

## 👨‍💻 Author

**Lyudmil Milenov**

GitHub: https://github.com/LMilenov

---

⭐ If you like this project, feel free to give it a star!
