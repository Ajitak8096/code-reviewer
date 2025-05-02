# 🧠 AI Code Review App

An interactive, AI-powered code editor that highlights JavaScript syntax and provides intelligent code reviews using a backend service. Built with **React**, **Vite**, **PrismJS**, and a lightweight code editor component, this app helps developers get real-time feedback on their code.

---

## 📌 Features

- ✍️ Write and edit JavaScript code in the browser
- 🎨 Real-time syntax highlighting with PrismJS
- 🔍 Get AI-generated code reviews with one click
- ⚡ Super fast development with Vite
- 💬 Clear UI with separated code and review panels

---

## 🚀 Technologies Used

### 🖥️ Frontend

| Technology                | Purpose                                      |
|--------------------------|----------------------------------------------|
| React                    | UI library for component-based architecture  |
| Vite                     | Fast development build tool                  |
| PrismJS                  | Syntax highlighting for code                 |
| react-simple-code-editor | Lightweight code editor component            |
| Axios                    | Handles HTTP requests to the backend         |
| CSS                      | Custom styles for layout and UI              |

### 🧠 Backend (Expected)

| Technology     | Purpose                                       |
|----------------|-----------------------------------------------|
| Node.js + Express.js | Handles API requests and routes            |
| OpenAI API (or similar) | Generates intelligent code reviews     |

---

## 🔁 Workflow

1. **User opens the web app**
   - The editor loads with some default JavaScript code.
2. **User edits the code**
   - Real-time syntax highlighting is applied with PrismJS.
3. **User clicks "Review"**
   - Sends a `POST` request to the backend at `http://localhost:3000/ai/get-review` with the code.
4. **Backend processes and replies**
   - AI analyzes the code and sends back suggestions or feedback.
5. **Frontend displays review**
   - The review is rendered in a separate panel beside the code editor.

---

## 📂 Folder Structure

