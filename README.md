# T-Access-Fullstack (Windows Working Version)

This is a **full-stack project** with a **Node.js backend** using Microsoft Access (ODBC) and a **React/Vite frontend**.  
This version is configured to work on **Windows** due to ODBC and Node architecture requirements.

---

## 📁 Project Structure

t-access-fullstack/
├── backend/ (Node 18, 32-bit, Access ODBC)
├── frontend/ (Node 22, 64-bit, Vite + React)
├── README.md
└── .gitignore

---

## ⚙️ Node Versions

- **Backend**: Node 18 (32-bit) → required for Access ODBC
- **Frontend**: Node 22+ (64-bit) → required for Vite / Rollup

> ⚠️ Make sure to use **NVM** to switch Node versions per folder.

---

## 🟢 Running the Backend

1. Open **VS Code** or terminal in `backend/` folder.
2. Switch Node version to 32-bit:

```bash
nvm use 18.19.0 32

---

## 3.Install dependencies (if not done yet):
`npm install

---

## 4. Start the backend server:
`npm start

Server runs on http://localhost:5000

API endpoint: http://localhost:5000/api/students

## Running the Frontend

Open a separate VS Code window / terminal in frontend/ folder.

Switch Node version to 64-bit:

`nvm use 22.12.0


Install dependencies (first-time setup):

`npm install


Start the frontend server:

`npm run dev


Frontend runs on http://localhost:5173/

It fetches data from backend API.

---

⚠️ Notes

Do NOT mix Node versions in a single terminal — backend must run on 32-bit Node, frontend on 64-bit Node.

package-lock.json is not included due to cross-architecture compatibility.

.gitignore excludes all node_modules and logs.
```
