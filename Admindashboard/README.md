# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

Here is a **clean, professional, production-quality README.md** for your Admin Dashboard project.
You can **copy-paste it directly** into your repository.

---

# **README.md**

# **Admin Dashboard**

A modern, fast, and lightweight Admin Dashboard built using **React**, **Vite**, **TailwindCSS**, and several modern UI/animation libraries.
This project does **not** require `node_modules` to be pushed to GitHub — instead, all dependencies are installed using `npm install` based on the `package.json` and `package-lock.json`.

---

## 🚀 **Features**

* ⚡️ Vite-powered fast development
* 🎨 Tailwind CSS styling
* 📊 Beautiful charts using Recharts
* 🎥 Animations using Framer Motion, GSAP & Animate.css
* 🔗 React Router for navigation
* 🌐 API requests using Axios
* 🔧 ESLint setup for clean code

---

## 📂 **Project Structure**

```
AdminDashboard/
│
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   └── main.jsx
│
├── package.json
├── package-lock.json
└── vite.config.js
```

---

## 📦 **Installing Dependencies (`node_modules`)**

### 🔥 **Important:**

You **do NOT** need to download or push `node_modules`.
It will be created automatically by running one command.

### ✅ **Steps to install dependencies**

1. Open a terminal in the project root:

```
D:\PathToPages\Backend\AdminDashboard
```

2. Run:

```bash
npm install
```

This will automatically create:

```
D:\PathToPages\Backend\AdminDashboard\node_modules
```

### 📌 If you want a clean install (recommended for production):

```bash
npm ci
```

This installs dependencies exactly as locked in `package-lock.json`.

---

## 📜 **Dependencies Used**

### **Main Dependencies**

```
animate.css
axios
framer-motion
gsap
lucide-react
react
react-dom
react-router-dom
recharts
```

### **Dev Dependencies**

```
@eslint/js
@types/react
@types/react-dom
@vitejs/plugin-react
autoprefixer
eslint
eslint-plugin-react-hooks
eslint-plugin-react-refresh
globals
postcss
tailwindcss
vite
```

---

## ▶️ **Available Scripts**

### **Start development server**

```bash
npm run dev
```

### **Build for production**

```bash
npm run build
```

### **Preview production build**

```bash
npm run preview
```

### **Run linter**

```bash
npm run lint
```

---

## 🛠️ **Tech Stack**

| Tool                     | Purpose             |
| ------------------------ | ------------------- |
| **React 19**             | UI Framework        |
| **Vite 7**               | Development & Build |
| **TailwindCSS**          | Styling             |
| **Recharts**             | Data Visualization  |
| **Axios**                | API Calls           |
| **Framer Motion / GSAP** | Animations          |
| **ESLint**               | Code Quality        |

---

## ⚠️ Do NOT Commit `node_modules`

Your `.gitignore` should contain:

```
node_modules/
```

Reason:

* It’s huge
* Regenerated automatically
* Causes repo issues
* Not needed for deployment

All environments (local or servers) should run:

```
npm install
```

---

## 🧩 **Troubleshooting**

### `npm install` fails

Try:

```bash
rm -rf node_modules package-lock.json
npm install
```

### Tailwind not working

Rebuild dev server:

```bash
npm run dev
```

### Missing modules

Run:

```bash
npm install
```

---

## 📧 **Support**

If you face installation or build issues, open an issue in the repo or contact the maintainer.
