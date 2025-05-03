## Introduction

This **Clay GTM Platform** repo is a front-end prototype built by reverse-engineering the visual style of [clay.com](https://clay.com). I spotted their clean, scroll-driven storytelling on a popular navbar gallery and decided to rebuild the look and feel from scratch. While it doesn’t power a real SaaS backend, it demonstrates how you might structure and style a modern Go-To-Market landing page using Vue 3, Tailwind CSS, and TypeScript.

---

## Why This Project Exists

- **Design Deep-Dive**: I wanted hands-on practice dissecting a production-quality SaaS homepage.  
- **Storytelling Layout**: Clay’s smooth scroll transitions, trust-builder sections, and feature spotlights taught me new layout tricks.  
- **Rebuild & Learn**: By copying their animations and component structure, I honed my skills in Vue 3 composition, modular CSS, and responsive layouts.

---

## Live Preview

> _This is purely a static front-end demo. No sign-ups, data saving, or real API calls._

---

## Getting Started

1. **Install dependencies**  
   ```bash
   npm install
   ```
2. **Run development server**  
   ```bash
   npm run dev
   ```
3. **Build for production**  
   ```bash
   npm run build
   ```
4. **Lint your code**  
   ```bash
   npm run lint
   ```

---

## Recommended IDE Setup

- **VS Code** with the following extensions:  
  - Volar (for Vue 3 + TS)  
  - ESLint  
  - Prettier  
- **Disable** Vetur if you have it installed, to avoid conflicts with Volar.

---

## TypeScript + Vue Tips

- Use `vue-tsc --noEmit` for type-checking `.vue` files instead of plain `tsc`.  
- Make sure Volar’s **Take Over Mode** is enabled so you get full IntelliSense in templates.

---

## Code Structure

\`\`\`plaintext
src/
 ┣ assets/         # images, SVGs, video snippets
 ┣ components/     # reusable UI pieces
 ┣ views/          # page-level Vue components
 ┣ router/         # Vue Router setup
 ┣ stores/         # Pinia stores or other state
 ┣ App.vue         # root component
 ┗ main.ts         # app bootstrap
\`\`\`

---

## Built With

- [Vue 3](https://vuejs.org/)  
- [Tailwind CSS](https://tailwindcss.com/)  
- [TypeScript](https://www.typescriptlang.org/)  
- [Vite](https://vitejs.dev/)  

---

> _This project is purely a front-end storytelling exercise—no backend included!_
