# 🧠 AI Code Review App

An interactive, AI-powered JavaScript code editor that provides real-time intelligent code reviews.

Built with **React**, **Vite**, **PrismJS**, and a lightweight code editor, this platform helps developers learn better coding practices, receive instant feedback, and enhance code quality — all from the browser.

---

## 🌟 Motivation

As a developer and student, I often needed feedback on the code I wrote — especially to learn best practices, identify mistakes, and write clean, reusable functions. Instead of relying on forums or waiting for mentors, I decided to build my own tool to:

- Instantly review JavaScript code with AI assistance
- Understand why certain coding practices are bad
- Learn and apply better practices interactively
- Encourage clean code habits and documentation awareness

---

## 📸 Demo

![Screenshot](https://github.com/user-attachments/assets/d363bfdc-9bbb-4f31-90a1-a10a5c4fef2a)

**🔗 Project Link:** [AI Code Review App](https://code-reviewer-six-phi.vercel.app/)

---

## ✨ Features

- ✍️ **Live JavaScript Code Editor** – Write code with syntax highlighting.
- 🤖 **AI-Powered Code Review** – Get detailed explanations, suggestions, and fixes.
- 📤 **One-Click Review** – Submit code to the backend with a single click.
- 🧠 **Educational Focus** – Learn from AI feedback with context and best practices.
- 🖥️ **User-Friendly Interface** – Clear and split UI for coding and reviewing.

---

## ⚙️ Tech Stack

### 🖥️ Frontend

| Technology                 | Purpose                                 |
|---------------------------|-----------------------------------------|
| React                     | Component-based UI development          |
| Vite                      | Fast build and development environment  |
| PrismJS                   | Syntax highlighting                     |
| react-simple-code-editor  | Lightweight code editor with PrismJS    |
| Axios                     | Sending HTTP requests to backend        |
| CSS                       | Custom UI styling                       |

### 🧠 Backend (Expected Setup)

| Technology     | Purpose                                |
|----------------|----------------------------------------|
| Node.js + Express.js | Backend server for handling requests |
| OpenAI API (or similar) | Generate code reviews and analysis   |

---

## 🔁 How It Works

1. **Launch the Web App**  
   Editor loads with starter JavaScript code.

2. **Write Your Code**  
   The syntax-highlighting editor gives a clean writing experience.

3. **Click “Review”**  
   Your code is sent via a POST request to the backend.

4. **AI Review Generated**  
   Backend processes your code using AI and sends back a structured review.

5. **Read & Learn**  
   Suggestions appear beside the code — showing issues, context, and improvements.

---

## 📂 Project Structure (Frontend)

src/
├── components/
│ ├── CodeEditor.jsx # Main code editor using PrismJS
│ └── ReviewPanel.jsx # Panel to show AI feedback
├── App.jsx # Root component
├── main.jsx # Entry point
├── api.js # Axios config for API requests
├── styles.css # Custom styles
public/
├── index.html # HTML template


---

## 📌 Next Steps / Enhancements

- Support for multiple languages (e.g., Python, Java)
- Inline code annotations instead of side panel
- Dark mode toggle
- User code history or save feature
- Rate feedback quality to improve AI suggestions

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/ai-code-review-app

# Navigate to the project folder
cd ai-code-review-app

# Install dependencies
npm install

# Start the frontend
npm run dev
