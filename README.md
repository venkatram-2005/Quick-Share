# 🚀 Quick Share
**Quick Share** is a lightweight and responsive web app designed for fast and secure text and file sharing. Whether you're sharing quick notes or sending important files, Quick Share gives you a seamless experience with a clean UI, unique shareable links, and optional data expiry — all powered by Supabase and built with modern frontend tools.
**Quick Share** is a sleek and minimal web app for seamless text and file sharing. Built with **React + TypeScript + Vite**, it leverages **Supabase** for backend services and uses **ShadCN UI** for an elegant and accessible user interface.

---

## ✨ Features

- 📄 Instantly share text snippets
- 📁 Secure file sharing with auto-expiry
- 🔗 Unique shareable links
- 🔒 End-to-end encryption for sensitive data 
- ⚡ Fast, responsive, and mobile-friendly UI
- ☁️ Supabase-powered backend (Auth, DB, Storage)

---

## 🛠️ Tech Stack

| Frontend             |  Backend / Services        |  UI / Styling         |
|----------------------|----------------------------|---------------------- |
| React + TypeScript   | Supabase (Database + Auth) | ShadCN + Tailwind CSS |
| Vite (Bundler)       | React Query (data sync)    | Lucide Icons          |

---

## 📦 Getting Started

### 1. Clone the Repository

git clone https://github.com/venkatram-2005/Quick-Share.git
cd Quick-Share


### 2. Install Dependencies

npm install

### 3. Start the Development Server

npm run dev

Your app will be running at [http://localhost:5173](http://localhost:5173)

---

## 📁 Scripts

| Script    | Description                   |
| --------- | ----------------------------- |
| `dev`     | Runs the app in dev mode      |
| `build`   | Builds the app for production |
| `preview` | Preview the production build  |
| `lint`    | Runs ESLint on codebase       |

---

## 📂 Project Structure

```text
quick-share/
├── public/                # Static files (favicon, etc.)
├── src/                   # Main source code
│   ├── components/        # Reusable UI components
│   ├── lib/               # Utility functions (Supabase, helpers)
│   ├── pages/             # App pages/routes (e.g., TextShare, FileUpload)
│   ├── hooks/             # Custom React hooks
│   ├── index.tsx          # Entry point
│   └── App.tsx            # Root component
├── supabase/              # Supabase-related config / SQL / seed scripts
├── .gitignore             # Ignored files and folders for git
├── README.md              # Project documentation
├── bun.lockb              # Bun package lock (if using Bun)
├── components.json        # ShadCN-generated config
├── eslint.config.js       # ESLint configuration
├── index.html             # Root HTML file (for Vite)
├── package.json           # Project metadata and scripts
├── package-lock.json      # NPM lock file
├── postcss.config.js      # PostCSS configuration
├── tailwind.config.ts     # Tailwind CSS configuration
├── tsconfig.json          # Global TypeScript configuration
├── tsconfig.app.json      # App-specific TS settings
├── tsconfig.node.json     # Node-specific TS settings
├── vite.config.ts         # Vite configuration


---

## 📝 License

This project is licensed under the **MIT License**.

---

## 🔗 Live Demo

📍 [quick-share-now.vercel.app](https://quick-share-now.vercel.app) *(Replace with your deployed URL if not set up yet)*

```
