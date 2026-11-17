# ⚖️ NyayaSetu AI
### Justice Made Simple for Every Indian

NyayaSetu AI is an AI-powered legal assistance platform designed to make Indian legal information easier to understand and access. It helps citizens explore their legal rights, understand laws, access legal document templates, and get guidance through an AI-powered chatbot.

---

## 📖 About the Project

Understanding legal rights and procedures can be difficult for ordinary citizens because legal information is often complex and difficult to access.

NyayaSetu AI aims to bridge this gap by providing a simple, accessible platform where users can explore Indian laws, understand their rights, access useful legal resources, and receive AI-assisted legal guidance.

The project focuses on improving legal awareness and making legal information more accessible to everyone.

## ✨ Features

- ⚖️ **Know Your Rights:** Explore important legal rights and provisions under Indian law.
- 🔍 **Legal Search:** Search and explore legal information using relevant sections and keywords.
- 🤖 **AI Legal Assistant:** Ask legal questions and receive AI-assisted explanations.
- 📄 **Legal Document Templates:** Access useful templates for legal applications, complaints, and notices.
- 🚨 **FIR Assistance:** Learn about the FIR process and access related information.
- 🌐 **Multilingual Support:** Designed to make legal information accessible in multiple languages.
- 🔐 **User Authentication:** User registration and login functionality.
- 📚 **Legal Awareness:** Learn about laws, legal procedures, and citizen rights.

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Frontend | React.js, JavaScript, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Authentication | Based on implemented authentication system |
| Development Tools | VS Code, MongoDB Compass |

## 📂 Project Structure

```text
NyayaSetu-AI/
│
├── client/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
│
├── server/
│   ├── routes/
│   ├── models/
│   ├── package.json
│   └── ...
│
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

*The structure above is a simplified overview of the project.*

## 🚀 Getting Started

Follow these steps to run NyayaSetu AI locally.

### Prerequisites

- Node.js and npm
- MongoDB (local installation or MongoDB Atlas)
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/RudraMilke/NyayaSetu-AI.git
cd NyayaSetu-AI
```

### 2. Set Up the Backend

```bash
cd server
npm install
```

Create a `.env` file inside the server folder and configure the environment variables required by your backend.

Example:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Use the actual variable names required by your backend code.

Start the backend using the script configured in your `server/package.json`, for example:

```bash
npm run dev
```

### 3. Set Up the Frontend

Open another terminal:

```bash
cd client
npm install
```

Configure the frontend API URL in the environment file if your application uses one.

For Vite projects, an example is:

```env
VITE_API_URL=http://localhost:5000
```

Use the variable name expected by your frontend code.

Start the frontend:

```bash
npm run dev
```

Open the local URL displayed in your terminal.

## 🔐 Environment Variables

Environment variables contain configuration details such as database connection strings, API URLs, and authentication secrets.

Never upload actual `.env` files or private credentials to GitHub.

## ☁️ Deployment

The project is intended to be deployed using:

| Component | Hosting Platform |
|---|---|
| Frontend | Vercel |
| Backend | Render |
| Database | MongoDB Atlas |

Deployment is a work in progress.

## 🎯 Future Scope

- Improve AI-generated legal explanations.
- Expand the Indian laws and legal information database.
- Improve regional language support.
- Add more legal document templates.
- Enhance legal aid discovery and accessibility.
- Improve the platform's overall user experience.

## ⚠️ Disclaimer

NyayaSetu AI is an educational and legal awareness project. The information provided through the platform is intended for general informational purposes and should not be considered a substitute for professional legal advice.

Users should consult a qualified legal professional for advice regarding specific legal matters.

## 👨‍💻 Developer

**Rudra Milke**

- GitHub: [@RudraMilke](https://github.com/RudraMilke)
- Project Repository: [NyayaSetu AI](https://github.com/RudraMilke/NyayaSetu-AI)

---

<p align="center">
  ⭐ If you find this project useful, consider giving it a star!
</p>