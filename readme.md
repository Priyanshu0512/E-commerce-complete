# Forever Full Stack - E-commerce Store

This repository contains the **Admin Panel** for the "Forever Full Stack" project — a modular, scalable web application using modern React and Vite tooling. The admin interface is designed for managing users, content, and configurations of the overall full-stack system.

---

## 📦 Tech Stack

- **Frontend Framework**: React 18
- **Routing**: React Router v6
- **HTTP Client**: Axios
- **Notifications**: React Toastify
- **Styling**: Tailwind CSS with PostCSS
- **Bundler**: Vite
- **Linting**: ESLint with plugins for React and Hooks
- **Language Support**: TypeScript-ready (via type definitions)
- **Environment Management**: `.env` based config

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone <repo-url>
cd forever-full-stack/admin
```

### Install Dependencies

```bash
npm install
```

### Start the Development Server

```bash
npm run dev
```

Navigate to `http://localhost:5173` in your browser to access the app.

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

---

## 🛠 Scripts

| Script            | Purpose                                          |
| ----------------- | ------------------------------------------------ |
| `npm run dev`     | Launches local dev server with hot reload        |
| `npm run build`   | Generates an optimized production build          |
| `npm run preview` | Serves the production build locally              |
| `npm run lint`    | Runs ESLint with strict config and zero warnings |

---

## 📁 Project Structure Overview

```
forever-full-stack/
└── admin/
    ├── .env                   # Local environment variables
    ├── .eslintrc.cjs          # ESLint configuration
    ├── index.html             # HTML entry point
    ├── package.json           # Project metadata and scripts
    ├── postcss.config.js      # PostCSS setup for TailwindCSS
    ├── tailwind.config.js     # Tailwind customization
    ├── public/                # Static assets
    └── src/
        ├── components/        # Reusable UI components
        ├── pages/             # Page-level React components
        ├── services/          # Axios HTTP utilities
        ├── routes/            # Route definitions
        ├── styles/            # Tailwind base layers
        └── main.jsx           # Root React entry
```

This structure helps maintain separation of concerns and promotes scalable architecture.

---

## ✅ Features

- Fast Hot Module Reloading with Vite
- Modular React component structure
- Built-in ESLint configuration to ensure code quality
- Responsive UI with utility-first Tailwind CSS
- Environment-based configuration with `.env` files
- Integrated notification system for better UX
- Easy routing and state management using idiomatic React patterns

---

## 🧰 Additional Notes

- Code is optimized for readability, maintainability, and scalability.
- Tailwind config can be customized further for themes, colors, or responsive breakpoints.
- Vite enables blazing fast refresh and build performance with native ES module support.
