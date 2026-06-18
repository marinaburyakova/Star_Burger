# 🍔 Cosmic Burger Constructor

A modern, feature-rich burger constructor application with real-time order feed, user authentication, and a cosmic theme.

![React](https://img.shields.io/badge/React-18.x-61dafb?style=flat&logo=react)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-2.x-764abc?style=flat&logo=redux)
![Vite](https://img.shields.io/badge/Vite-5.x-646cff?style=flat&logo=vite)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-f7df1e?style=flat&logo=javascript)

---

##  Features

- 🍔 **Interactive Burger Constructor** – Drag & drop ingredients, add/remove items, see real-time price updates.
-  **Real-Time Order Feed** – Simulated WebSocket feed with live order status updates (pending → preparing → ready).
-  **User Authentication** – Registration, login, profile management, and order history.
-  **Cosmic Theme** – Animated starfield with parallax effect, nebula-like gradients, and neon glow effects.
-  **Fully Responsive** – Optimized for desktop, tablet, and mobile devices with a burger menu.
-  **High Performance** – `useMemo`, `useCallback`, `React.memo`, lazy loading, and virtual scrolling for smooth UX.
-  **Modular Architecture** – Feature-based folder structure, Redux Toolkit, and reusable hooks.

---

## Live Demo

The application simulates a real-time ordering experience:

- New orders appear every 15 seconds (demo mode).
- Order statuses automatically update: `pending` → `preparing` → `ready`.
- All updates happen in real-time through a mock WebSocket service.

---

##  Tech Stack

### Frontend
- **React 18** – Component-based UI development.
- **Redux Toolkit** – State management with slices, thunks, and entity adapters.
- **React Router** – Client-side routing (optional, used for deep linking).
- **Vite** – Fast build tool with HMR and optimized bundling.
- **CSS3** – Custom styles with animations, themes, and responsive design.

### Development Tools
- **ESLint** – Code linting and formatting.
- **Prettier** – Consistent code style.
- **React DevTools** – Component and performance debugging.
