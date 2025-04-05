# Clay GTM Platform

![Scroll 1](/frontend/src/assets/readme/1scroll.png)


## Introduction

**Clay GTM Platform** is a concept-level front-end project designed to showcase what a modern, clean, and highly visual SaaS homepage could look like for a Go-To-Market (GTM) platform.  
This project brings together elements of automation, AI research integration, and growth tooling into a unified interface — but strictly on the presentation level.

The layout is entirely front-end, built with Vue 3 and styled using Tailwind CSS, and structured around modular and scalable component logic.  
While it doesn't include backend functionality, it is designed as if it were the front door to a powerful GTM SaaS product.

---

## Why I Made It

I created this project as an exercise in creative front-end storytelling.

Rather than just showcasing typical SaaS UI patterns, I wanted to build something that looks unique, feels delightful, and still follows solid structural principles.  
The goal was to design something that's "different but functional" — a clean dev stack under the hood, and a playful, expressive visual layer on top.

This was also a chance to explore layout strategy for scroll-based storytelling, customer credibility sections, feature highlights, and animated showcases — all of which are critical in early-stage B2B SaaS marketing.

---

## Screenshots

### Full Page Scroll Preview


---

## Project Setup

Install dependencies:

```sh
npm install
```

Start a dev server with hot reload:

```sh
npm run dev
```

Build for production:

```sh
npm run build
```

Run linter:

```sh
npm run lint
```

---

## Recommended IDE Setup

- [Visual Studio Code](https://code.visualstudio.com/)
- [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (recommended for Vue 3 + TypeScript support)

_Disable Vetur to prevent conflicts._

---

## TypeScript + Vue Note

By default, TypeScript does not handle `.vue` files well.  
To make type checking accurate and error-free:

- Use `vue-tsc` for type checks instead of `tsc`.
- Ensure Volar is active in your IDE.

---

## Project Structure

```
src/
 ┣ assets/
 ┃ ┣ logo/
 ┃ ┣ png/
 ┃ ┣ svg/
 ┃ ┣ video/
 ┃ ┗ readme/        
 ┣ components/       
 ┣ views/
 ┃ ┗ HomeView.vue    
 ┣ App.vue           
 ┣ main.ts           
 ┣ router/
 ┃ ┗ index.ts        
 ┗ stores/
    ┗ counter.ts     
```

---

## Built With

- Vue 3
- Tailwind CSS
- TypeScript
- Vite

---

> This project is a showcase of what frontend storytelling can look like.