# Guilherme Cantarino | Software Engineer Portfolio

![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

Welcome to my professional portfolio! I am a **Software Engineer** specializing in building high-performance, scalable web systems and mobile applications. This project showcases my work, skills, and technical expertise using modern tech stacks.

## 🚀 Live Demo

Check out the live version here: [https://cantarinog.github.io/portfolio/](https://cantarinog.github.io/portfolio/)

---

## 🛠 Tech Stack

- **Framework**: [Astro](https://astro.build/) (Static Site Generation for speed)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (Utility-first styling & responsiveness)
- **Language**: [TypeScript](https://www.typescriptlang.org/) (Type safety and maintainability)
- **Animations**: CSS Transitions & JavaScript Intersection Observer
- **Deployment**: [GitHub Actions](https://github.com/features/actions) (Automated CI/CD)

---

## ✨ Key Features

- **Blazing Fast**: Built with Astro's zero-JS-by-default architecture.
- **Micro-interactions**: Smooth custom animations and transitions for a premium feel.
- **Dynamic Projects**: Interactive product showcase with image slideshows and modal details.
- **Theme Toggle**: Full Support for **Dark Mode** and **Light Mode**.
- **Responsive**: pixel-perfect layout from mobile to ultra-wide displays.
- **SEO Optimized**: Fully compliant with modern SEO standards (Meta tags, OpenGraph, JSON-LD).
- **Accessibility**: Focused on semantic HTML, color contrast, and keyboard navigation.

---

## 📁 Project Structure

```text
/
├── .github/workflows/    # CI (Validation) & CD (Deployment) workflows
├── public/               # Static assets (favicons, etc.)
├── src/
│   ├── assets/           # Project images and personal photos
│   ├── components/       # Reusable Astro components (Navbar, Modal, etc.)
│   ├── data/             # Project data management (JSON)
│   ├── pages/            # Page-level components (index.astro)
│   └── styles/           # Global CSS and Tailwind directives
├── astro.config.mjs      # Astro & Vite configuration
└── package.json          # Project dependencies and scripts
```

---

## ⚙️ Local Development

### Prerequisites

- [Node.js](https://nodejs.org/) (v18.14.1 or higher)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/CantarinoG/portfolio.git
   ```
2. Navigate to the project directory:
   ```bash
   cd portfolio
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Commands

| Command           | Action                                        |
| :---------------- | :-------------------------------------------- |
| `npm run dev`     | Starts local dev server at `localhost:4321`   |
| `npm run build`   | Builds the production-ready site into `dist/` |
| `npm run preview`      | Previews the local build                         |
| `npm run lint`         | Runs ESLint to catch code errors                 |
| `npm run format:check` | Checks if code follows Prettier styles           |

---

The project uses **GitHub Actions** for an automated two-stage pipeline:

1.  **CI (Validation)**:
    - Triggered on every **Pull Request** to `main`.
    - Runs linting, formatting checks, and a production build.
    - Ensures code quality and prevents "broken" merges.

2.  **CD (Deployment)**:
    - Triggered on every **Push** (or Merge) to `main`.
    - Automatically builds and deploys the site to **GitHub Pages**.

### Code Quality
We use **ESLint** for catch logic errors and **Prettier** for consistent formatting. You can run these checks locally using the commands listed above.

---

Developed with ❤️ by **Guilherme Cantarino**
