# AI Powered Resume Builder

An intelligent full-stack resume builder that helps users create professional, ATS-friendly resumes with the power of AI.

---

## Table of Contents

* [About the Project](#about-the-project)
* [Project Overview](#project-overview)
* [Key Features](#key-features)
* [Tech Stack](#tech-stack)
* [Dependencies](#dependencies)
* [Installation & Setup](#installation--setup)
* [Environment Variables](#environment-variables)
* [Folder Structure](#folder-structure)
* [Contributions](#contributions)
* [How to Contribute](#how-to-contribute)
* [License](#license)
* [Contact](#contact)

---

## About the Project

**AI Powered Resume Builder** is a modern full-stack web application designed to make resume creation easier, faster, and more professional.

The application allows users to create, customize, and manage resumes while using **AI-powered features** to improve resume content and make it more effective for job applications.

The main goal of this project is to simplify the resume-building process and help users create professional resumes without needing advanced design or writing skills.

---

## Project Overview

AI Powered Resume Builder combines a modern web interface with a powerful backend and AI integration.

### 🎯 Project Goals

* Create professional resumes quickly
* Provide AI-assisted resume content generation
* Allow users to manage multiple resumes
* Store resume data securely
* Provide a simple and responsive user experience
* Make resumes suitable for modern job applications

### 📌 Project Type

**Full-Stack Web Application**

### 🤖 AI Integration

AI is used to assist users with resume content such as:

* Professional summaries
* Job descriptions
* Skills
* Resume improvements
* Content suggestions

---

## Key Features

* 🤖 **AI-Powered Resume Assistance** — Generate and improve resume content using AI.
* 📝 **Resume Builder** — Create professional resumes through an easy-to-use interface.
* 🎨 **Modern Resume Templates** — Build clean and professional-looking resumes.
* 🔐 **User Authentication** — Secure user registration and login.
* 🔑 **JWT Authentication** — Secure API authentication using JSON Web Tokens.
* 📄 **Resume Management** — Create, update, and manage resumes.
* 🖼️ **Profile Image Upload** — Upload and manage profile images.
* ☁️ **ImageKit Integration** — Cloud-based image storage and optimization.
* 💾 **MongoDB Database** — Store users and resume information.
* 📱 **Responsive Design** — Works across desktop, tablet, and mobile devices.
* ⚡ **REST API** — Backend APIs for managing users and resumes.
* 🔒 **Protected Routes** — Authenticated users can access protected resources.

---

## Tech Stack

### Frontend

**React.js** · **JavaScript** · **Tailwind CSS** · **Axios**

### Backend

**Node.js** · **Express.js** · **MongoDB** · **Mongoose**

### Authentication & Security

**JWT** · **bcrypt**

### AI

**AI API**

### Image & File Storage

**ImageKit**

### Tools

**Git** · **GitHub** · **VS Code** · **npm** · **Vercel**

---

## Dependencies

### Frontend

Major frontend dependencies may include:

```json
{
  "react": "^18.x",
  "JavaScript": "^5.x",
  "axios": "^1.x",
  "tailwindcss": "^3.x"
}
```

### Backend

Major backend dependencies may include:

```json
{
  "express": "^4.x",
  "mongoose": "^8.x",
  "jsonwebtoken": "^9.x",
  "bcrypt": "^5.x",
  "cors": "^2.x",
  "dotenv": "^16.x"
}
```

> **Note:** The exact versions may vary depending on the current `package.json` files.

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/nazmul-07/resume_builder_frontend.git
```

Navigate into the project:

```bash
cd resume_builder_frontend
```

---

### 2. Install Dependencies

If the project has separate frontend and backend folders:

```bash
cd frontend
npm install
```

Then:

```bash
cd ../backend
npm install
```

---

### 3. Set Up Environment Variables

Create a `.env` file inside the backend directory.

> ⚠️ Never commit your `.env` file or API keys to GitHub.

---

### 4. Run the Backend

```bash
cd backend
npm run dev
```

The backend will run on:

```text
http://localhost:5000
```

---

### 5. Run the Frontend

Open another terminal:

```bash
cd frontend
npm run dev
```

The frontend will normally run on:

```text
http://localhost:5173
```

---

## Folder Structure

```plaintext
AI-Resume-Builder/
│
├── frontend/
│   │
│   ├── public/
│   │
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── layouts/
│   │   ├── hooks/
│   │   ├── services/
│   │   ├── utils/
│   │   ├── types/
│   │   ├── assets/
│   │   └── App.tsx
│   │
│   ├── package.json
│   └── vite.config.ts
│
├── backend/
│   │
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   ├── services/
│   │   ├── utils/
│   │   └── config/
│   │
│   ├── package.json
│   └── server.js
│
├── .gitignore
└── README.md
```

---

## API Overview

The backend provides RESTful APIs for handling users and resumes.

### Authentication

```text
POST   /api/auth/register
POST   /api/auth/login
GET    /api/auth/me
```

### Resume

```text
POST   /api/resumes
GET    /api/resumes
GET    /api/resumes/:id
PUT    /api/resumes/:id
DELETE /api/resumes/:id
```

### AI

```text
POST /api/ai/generate
POST /api/ai/improve
```

> API routes may differ depending on the current backend implementation.

---

## Screenshots

### 🏠 Landing Page

Add your project screenshot here:

```markdown
![Landing Page](./screenshots/landing-page.png)
```

### 📊 Dashboard

```markdown
![Dashboard](./screenshots/dashboard.png)
```

### 📄 Resume Builder

```markdown
![Resume Builder](./screenshots/resume-builder.png)
```

---

## Contributions

This project is primarily developed by **Md Nazmul Hosen**.

| Name            | Role                 | Contributions                                                                 |
| --------------- | -------------------- | ----------------------------------------------------------------------------- |
| Md Nazmul Hosen | Full-Stack Developer | Frontend, Backend, API Integration, Database, Authentication & AI Integration |

---

## How to Contribute

Contributions are welcome!

1. Fork the Project

2. Create your Feature Branch:

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes:

```bash
git commit -m "Add some AmazingFeature"
```

4. Push to the branch:

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request.

---

## Future Improvements

* [ ] More professional resume templates
* [ ] Advanced AI resume analysis
* [ ] ATS score checker
* [ ] Job description matching
* [ ] Resume PDF export improvements
* [ ] Cover letter generator
* [ ] More AI-powered writing tools
* [ ] Dark mode
* [ ] Resume sharing via public URL
* [ ] More customization options

---

## License

Distributed under the **MIT License**.

See `LICENSE` for more information.

---

## Contact

**Md Nazmul Hosen**

* 🐙 GitHub: [@nazmul-07](https://github.com/nazmul-07)
* 💼 LinkedIn: [LinkedIn Profile](https://www.linkedin.com/)
* 🌐 Portfolio: [Portfolio](https://yourportfolio.com)
* 📧 Email: [[your-email@example.com](mailto: ytnazmul535@gmail.com)]

---

## ⭐ Show Your Support

If you found this project useful or interesting, please consider giving it a ⭐ on GitHub.

<p align="center">
  <b>Built with ❤️ and lots of ☕ by Md Nazmul Hosen</b>
</p>

<p align="center">
  🚀 Keep Learning • Keep Building • Keep Growing
</p>
