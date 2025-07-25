# 🗂️ Storage Management Solution

A full-stack storage management application built with the **MERN** stack, featuring secure authentication, a dynamic dashboard, and full CRUD operations. This project demonstrates a complete workflow from frontend design to backend logic and database integration.


## 🚀 Features

- 🔐 User Authentication (JWT-based)
- 📦 Manage Storage Units & Items
- 🧾 Real-Time Dashboard
- 📝 Create, Read, Update, Delete functionality
- 🎨 TailwindCSS for sleek styling
- 🔄 Redux Toolkit for state management


## 🛠️ Tech Stack

- **Frontend:** React.js, Redux Toolkit, TailwindCSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas
- **Authentication:** JWT (JSON Web Tokens)


## ⚙️ Getting Started

### 📁 Clone the repository

```bash
git clone https://github.com/Tejaswini-M15/storage-management-solution.git
cd storage-management-solution
```

### 📦 Install dependencies

#### Backend
```bash
cd server
npm install
```

#### Frontend
```bash
cd client
npm install
```

### 🔑 Environment Setup
Create .env files in both the server/ and client/ folders with the following:

#### server/.env
```ini
MONGO_URI=your_mongo_db_uri
JWT_SECRET=your_jwt_secret
PORT=5000
```

#### client/.env
```ini
VITE_API_URL=http://localhost:5000
```

### ▶️ Run the App

#### Backend
```bash
cd server
npm start
```

#### Frontend
```bash
cd client
npm run dev
```

Open the app in your browser at: http://localhost:5173

### 📂 Folder Structure

```bash
storage-management-solution/
├── .idea/                  # IDE settings (optional)
├── app/                   # App router (Next.js 13+)
├── components/            # Reusable UI components
├── constants/             # Constant variables (routes, config, etc.)
├── hooks/                 # Custom React hooks
├── lib/                   # Utility functions and libs
├── public/                # Static files like images and icons
├── types/                 # TypeScript types
├── .env.example           # Example environment variables
├── .eslintrc.json         # ESLint config
├── .gitignore             # Git ignored files
├── components.json        # ShadCN / CLI UI config
├── next.config.ts         # Next.js configuration
├── package.json           # Project dependencies and scripts
├── package-lock.json      # Lockfile for npm
├── postcss.config.mjs     # PostCSS configuration
├── tailwind.config.ts     # Tailwind CSS configuration
├── tsconfig.json          # TypeScript compiler configuration
├── README.md              # Project overview and setup guide

```
## 👩‍💻 About Me

**Tejaswini Mohapatra** — CSE Undergrad | Frontend Enthusiast 💙

- 🐙 GitHub: [@Tejaswini-M15](https://github.com/Tejaswini-M15)
- 💼 LinkedIn: [Tejaswini Mohapatra](https://www.linkedin.com/in/tejaswinim15)

> If you found this project interesting, feel free to ⭐ star the repo and connect with me!
---




