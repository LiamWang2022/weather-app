# Webpack JS Template

A minimal and reusable Webpack 5 boilerplate for modern JavaScript projects.  
This template includes a ready-to-use development and production setup with support for HTML, CSS, and image assets.

---

## 🔧 Features & Plugins

This template includes the following tools and plugins:

- **webpack** – Core bundler
- **webpack-cli** – Webpack command line interface
- **webpack-dev-server** – Local development server with hot reloading
- **webpack-merge** – Merges base/common config with dev/prod configs
- **html-webpack-plugin** – Automatically injects bundled JS into HTML
- **html-loader** – Processes HTML files and their resources (e.g., `<img src="">`)
- **style-loader** + **css-loader** – Loads and injects CSS into JS
- **asset modules** – Loads images and other static assets (via `type: 'asset/resource'`)

---

## 📦 Installation

```bash
npm install
```
---

## ✍️ Files You Should Modify

When using this template to start a new project, we recommend updating the following files:

| File | What to Update | Why |
|------|----------------|-----|
| `package.json` | `"name"` | Change to your new project's name |
| `package.json` | `"version"` | Optional: Reset to `"1.0.0"` for a new project |
| `package.json` | `"description"` / `"author"` / `"repository"` | Update with your own info |
| `README.md` | Project title and description | Describe your actual project instead of the template |
| `src/index.js` | Your app logic | Replace with your own JS entry code |
| `src/style.css` | Your styles | Style your project however you like |
| `src/assets/` | Replace sample images | Add your own images, logos, etc. |
| `public/index.html` | Title, meta tags, favicon | Customize your HTML layout and SEO info |

These updates help personalize the project and make your GitHub repository reflect the real purpose of your new application.

---
