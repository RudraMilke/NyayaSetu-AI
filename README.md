# NyayaSetu AI

### Justice Made Simple for Every Indian

**NyayaSetu AI** is an AI-powered legal assistance platform designed to make Indian legal information more accessible and easier to understand. It helps citizens explore their legal rights, understand legal provisions, access document templates, and receive AI-assisted legal guidance through a unified platform.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Environment Configuration](#environment-configuration)
- [Deployment](#deployment)
- [Future Scope](#future-scope)
- [Disclaimer](#disclaimer)
- [Author](#author)

---

## About the Project

Access to legal information remains a challenge for many citizens due to complex legal terminology, limited awareness, and difficulty navigating legal procedures.

NyayaSetu AI aims to bridge this gap by providing a centralized platform for legal awareness and assistance. Users can explore Indian laws, understand their fundamental legal rights, access useful legal document templates, and interact with an AI-powered assistant to get simplified explanations of legal topics.

The project focuses on using technology to promote legal literacy, improve accessibility, and make essential legal information easier to understand.

## Key Features

- **Legal Rights Information:** Explore important legal rights and provisions under Indian law.
- **Legal Search:** Search for legal information using relevant sections and keywords.
- **AI-Powered Legal Assistant:** Interact with an AI assistant to receive simplified explanations of legal queries.
- **Legal Document Templates:** Access templates for commonly used legal documents, applications, and notices.
- **FIR Assistance:** Understand the FIR filing process and access related legal information.
- **Multilingual Accessibility:** Support for making legal information accessible to users in multiple languages.
- **User Authentication:** User registration and login functionality.
- **Legal Awareness Resources:** Access educational information about laws, rights, and legal procedures.

## Technology Stack

| Layer                   | Technology                         |
| ----------------------- | ---------------------------------- |
| Frontend                | React.js, JavaScript, Tailwind CSS |
| Backend                 | Node.js, Express.js                |
| Database                | MongoDB                            |
| Development Environment | Visual Studio Code                 |
| Database Management     | MongoDB Compass                    |

## Project Structure

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

*Note: This is a simplified representation of the project directory.*

## Getting Started

Follow the instructions below to set up and run the project locally.

### Prerequisites

Ensure that the following software is installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Git](https://git-scm.com/)
- [MongoDB](https://www.mongodb.com/)

### 1. Clone the Repository

```bash
git clone https://github.com/RudraMilke/NyayaSetu-AI.git
cd NyayaSetu-AI
```

### 2. Configure the Backend

Navigate to the server directory:

```bash
cd server
npm install
```

Create a `.env` file inside the `server` directory and configure the required environment variables.

Example:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Use the exact environment variable names expected by the backend implementation.

Start the backend:

```bash
npm run dev
```

### 3. Configure the Frontend

Open a separate terminal and navigate to the client directory:

```bash
cd client
npm install
```

Configure the backend API URL in the frontend environment file if required.

For a Vite-based application, the variable may look like:

```env
VITE_API_URL=http://localhost:5000
```

Start the frontend:

```bash
npm run dev
```

Open the local development URL displayed in the terminal.

## Environment Configuration

The application uses environment variables for configuration, including database connection details, API URLs, and authentication secrets.

For security:

- Never commit `.env` files to the repository.
- Keep database credentials and API keys private.
- Configure production environment variables directly through the hosting platforms.

## Deployment

The application is planned to use the following deployment architecture:

| Component | Platform      |
| --------- | ------------- |
| Frontend  | Vercel        |
| Backend   | Render        |
| Database  | MongoDB Atlas |

Deployment configuration and live application links will be added once the deployment process is complete.

## Future Scope

- Expand the legal information database with additional Indian laws and provisions.
- Improve AI-generated legal explanations and contextual responses.
- Extend regional language support.
- Introduce additional legal document templates.
- Improve legal aid discovery and accessibility.
- Enhance performance, security, and user experience.

## Disclaimer

NyayaSetu AI is an educational and legal awareness platform developed to simplify access to general legal information.

The information provided by the platform is intended for educational purposes only and does not constitute professional legal advice. Users should consult qualified legal professionals for advice concerning specific legal matters.

## Author

**Rudra Milke**

- GitHub: [RudraMilke](https://github.com/RudraMilke)
- Project: [NyayaSetu AI](https://github.com/RudraMilke/NyayaSetu-AI)

---

NyayaSetu AI — Making Legal Awareness More Accessible
