# 🚀 CodeForge AI – AI-Powered Browser IDE

CodeForge AI is a modern AI-powered web IDE that enables developers to write, edit, and execute code directly in the browser. It combines a powerful code editor, integrated terminal, AI-assisted coding, authentication, and real-time development tools into a seamless developer experience.

Built using **Next.js 15**, **Monaco Editor**, **WebContainers**, and **Ollama**, CodeForge AI brings the power of a desktop IDE to the web.

---

## ✨ Features

- 🔐 Secure authentication with **Google** and **GitHub OAuth**
- 📝 Powerful code editing with **Monaco Editor**
- 🤖 AI-powered coding assistant using **Ollama**
- 📂 Custom file explorer for project management
- 💻 Integrated terminal using **xterm.js**
- 🌐 Run applications directly in the browser with **WebContainers**
- 📦 Multiple project templates to kickstart development
- 🌙 Dark & Light mode support
- ⚡ Fast and responsive UI built with Next.js
- 📱 Fully responsive interface

---

## 🛠️ Tech Stack

| Layer | Technology |
|--------|------------|
| Framework | Next.js 15 (App Router) |
| Language | TypeScript |
| Styling | Tailwind CSS + ShadCN UI |
| Authentication | NextAuth (Google & GitHub OAuth) |
| Code Editor | Monaco Editor |
| AI Assistant | Ollama |
| Runtime | WebContainers |
| Terminal | xterm.js |
| Database | MongoDB |
| Package Manager | npm |

---

## 📂 Project Structure

```text
CodeForge-AI/
│
├── app/
├── components/
├── lib/
├── public/
├── styles/
├── hooks/
├── utils/
├── types/
├── prisma/
├── package.json
├── next.config.js
└── README.md
```

---

## 🚀 Core Functionalities

### 🔐 Authentication

- Google Login
- GitHub Login
- Secure session management with NextAuth

---

### 💻 Smart Code Editor

- Monaco Editor integration
- Syntax highlighting
- Auto indentation
- Multi-language support
- Keyboard shortcuts

---

### 🤖 AI Coding Assistant

Generate code using local LLMs powered by Ollama.

The AI assistant helps with:

- Code generation
- Debugging
- Refactoring
- Code explanation
- Development guidance

---

### 📁 Project Explorer

Manage your project files efficiently.

- Create files
- Rename files
- Delete files
- Organize folders

---

### 🌐 Browser Runtime

Run frontend applications directly inside the browser using WebContainers.

No additional local setup required for supported projects.

---

### 💻 Integrated Terminal

Execute commands without leaving the editor.

Powered by **xterm.js**.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| Ctrl + Space | Trigger AI Suggestions |
| Tab | Accept AI Suggestion |
| Double Enter | Quick AI Completion |

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/codeforge-ai.git
```

### Navigate to the Project

```bash
cd codeforge-ai
```

### Install Dependencies

```bash
npm install
```

---

## ⚙️ Environment Variables

Create a `.env.local` file and configure the following variables:

```env
AUTH_SECRET=

AUTH_GOOGLE_ID=
AUTH_GOOGLE_SECRET=

AUTH_GITHUB_ID=
AUTH_GITHUB_SECRET=

DATABASE_URL=

NEXTAUTH_URL=http://localhost:3000
```

---

## 🤖 Run Ollama

Install Ollama and start your preferred coding model.

Example:

```bash
ollama run codellama
```

---

## ▶️ Start Development Server

```bash
npm run dev
```

Visit:

```
http://localhost:3000
```

---


## 🔮 Future Improvements

- 🔥 Multi-file AI Context
- 🔥 Live Collaboration
- 🔥 GitHub Repository Integration
- 🔥 Docker Support
- 🔥 AI Code Review
- 🔥 Extension Marketplace
- 🔥 Real-time Pair Programming
- 🔥 Deployment Support (Vercel / Netlify)

---

## 💡 Why CodeForge AI?

CodeForge AI demonstrates the integration of modern web technologies, AI-assisted development, browser-based execution, authentication, and interactive development tools into a single platform. The project showcases full-stack development, developer tooling, and AI integration concepts in a practical real-world application.

---

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a star!
