# DevNexus

DevNexus is a full-stack developer platform designed to help users practice coding problems, submit solutions, and improve their problem-solving skills.

## 🚀 Features

* 🔐 User Authentication
* 👤 User Signup and Login
* 💻 Coding Problems
* 🧑‍💻 Online Code Editor
* ⚡ Run and Submit Code
* 🏆 Track Solved Problems
* 🤖 AI-powered DSA Tutor
* 🎥 Video Editorials for Problems
* 🛠️ Admin Panel
* 📊 Problem Management
* 🔒 Secure Authentication using JWT
* ☁️ Cloud-based Video Storage

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* JavaScript
* Tailwind CSS
* DaisyUI
* React Router
* Redux Toolkit
* Axios
* Monaco Editor

### Backend

* Node.js
* Express.js
* MongoDB
* Redis
* JWT
* Judge0 API
* Google Gemini API
* Cloudinary

## 📂 Project Structure

```text
DevNexus/
│
├── Frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── utils/
│   │   ├── authSlice.js
│   │   └── App.jsx
│   └── package.json
│
└── Backend/
    ├── src/
    │   ├── config/
    │   ├── controllers/
    │   ├── models/
    │   ├── routes/
    │   └── middleware/
    └── package.json
```

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd DevNexus
```

### 2. Setup Frontend

```bash
cd Frontend
npm install
npm run dev
```

The frontend will run on:

```text
http://localhost:5173
```

### 3. Setup Backend

Open another terminal:

```bash
cd Backend
npm install
nodemon src/index.js
```

The backend will run on:

```text
http://localhost:3000
```

## 🔑 Environment Variables

Create a `.env` file inside the Backend folder.

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
REDIS_PASS=your_redis_password
GEMINI_KEY=your_gemini_api_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

> Never upload your `.env` file or API keys to GitHub.

## 🤖 AI Tutor

DevNexus includes an AI-powered DSA tutor that helps users understand coding problems by providing explanations, hints, approaches, and debugging guidance.

## 🎥 Video Editorials

Each coding problem can have a video editorial that explains the problem and its solution. Videos are stored using Cloudinary and can be viewed directly from the problem page.

## 👨‍💻 Admin Features

Admins can:

* Create coding problems
* Delete coding problems
* Upload video editorials
* Manage problem content

## 🔮 Future Improvements

* More programming languages
* User progress dashboard
* Leaderboard
* Daily coding challenges
* Better AI explanations
* Discussion section
* Contest system
* Personalized learning paths

## 📌 Project Status

DevNexus is currently under active development.

## 👨‍💻 Author

**Prativa De**

Built as a full-stack learning and coding platform.
