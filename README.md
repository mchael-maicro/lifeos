# 🚀 LifeOS AI - The Ultimate Second Brain & Workspace

LifeOS AI is a massive, highly-modular front-end prototype designed to be the ultimate all-in-one digital workspace. It bridges the gap between task management, personal life tracking, business operations, and AI-powered content generation. 

Built with a sleek, premium dark-mode aesthetic (inspired by the "CRAVEAT" theme) and glassmorphism elements, this Single Page Application (SPA) feels like a native mobile app right in the browser.

## ✨ Core Features & Modules

This prototype includes over 20 completely integrated UI modules, categorized into five main pillars:

### 🧠 Core System (Productivity)
* **Dashboard:** A bird's-eye view of actionable tasks, focus time, and quick "Brain Dump" captures.
* **Deep Focus:** A distraction-free Pomodoro timer with a strict "Do Not Disturb" mode.
* **Habits & Routines:** Streak tracking for daily goals.
* **Calendar & Timeline:** Visual Gantt charts for project overlap and daily meeting agendas.

### 💎 Life & Wealth
* **Wallet & Finances:** Expense tracking, savings overview, and recent transaction logs.
* **Trading Portfolio:** Real-time crypto and stock market trend visualization.
* **Health & Vitals:** Cardiology tracking, blood pressure averages, and active medication logs.
* **E-Learning Hub:** Course progress tracking and module completion metrics.

### 🤖 AI & Workspace
* **AI Studio:** Sequential, step-by-step generative AI workflows (e.g., Content Creator Suite from ideation to media generation).
* **Smart Spaces:** An infinite canvas concept for dragging and dropping text, kanban boards, and AI prompts.
* **Logic Flows:** Visual, node-based automation building (Trigger ➔ AI Action ➔ Output).
* **Audio Studio:** A built-in mixing interface with a floating, globally active media player.

### 🏢 Pro Business Suites
* **TeamHub (HR):** Employee attendance, performance metrics, and recruitment pipelines.
* **AIZCRM:** Sales tracking, revenue metrics, and market share visualization.
* **E-Commerce:** Warehouse inventory management and product stock levels.
* **Travel & Logistics:** Flight booking overviews and live ride-tracking UI.

### 🔒 Security & System
* **Seamless Access (Auth):** A highly polished login/signup flow featuring social auth and biometric toggles.
* **Privacy & AppLock:** A UI for locking down specific integrations (WhatsApp, Instagram).
* **Stealth Mode:** A quick-toggle to instantly blur sensitive financial and health data from screen snoopers.
* **Auto-Lock:** An inactivity timer that secures the dashboard behind a PIN screen.

## 🛠️ Tech Stack
* **HTML5:** Semantic structure and Single Page Application (SPA) routing logic.
* **CSS3:** Native CSS variables, Flexbox/Grid layouts, glassmorphism (`backdrop-filter`), and smooth keyframe animations.
* **Vanilla JavaScript:** DOM manipulation, dynamic class toggling, inactivity timers, and mobile-responsive navigation handling.

## 📱 Native App Optimizations
The UI is heavily optimized for mobile devices, featuring:
* A dynamic Bottom Navigation Bar that replaces the desktop sidebar on smaller screens.
* Touch-optimized elements with `user-select: none` to prevent awkward highlighting.
* Smooth, iOS-style sliding screen transitions.

## 🚀 Getting Started
Currently, this repository contains the **Front-End UI Architecture**. 

1. Clone the repository.
2. Open `auth.html` or `index.html` directly in any modern web browser to interact with the prototype.
3. No build tools or package managers are required for the static UI.

## 🗺️ Roadmap / Next Steps
* [ ] **Backend Integration:** Connect to Supabase/Firebase for user authentication and real-time database storage.
* [ ] **AI API Wiring:** Connect the AI Studio modules to the Google Gemini API (Nano, Flash, and Lyria models) via a Node.js/Express backend.
* [ ] **PWA Conversion:** Add a `manifest.json` and service workers to make the app fully installable on mobile devices.
