# 🌐 Team Website

[![Live Preview](https://img.shields.io/badge/Live%20Preview-Visit%20Site-4f46e5?style=for-the-badge&logo=globe)](https://your-preview-link-here.com)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

Personal website of a freelance Web Designer, built with pure HTML5 and CSS3. The project was developed as a team using a Git workflow based on dedicated per-page branches and pull requests into an integration branch.

---

## 📋 Table of Contents

- [Demo](#-demo)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Git Workflow](#-git-workflow)
- [CSS Architecture](#-css-architecture)
- [Pages](#-pages)
- [Team](#-team)

---

## 🚀 Demo

🔗 **[View live site →](https://your-preview-link-here.com)**

---

## 📁 Project Structure

```
team-website/
├── assets/
├── css/
│   ├── base.css               ← global variables & reset
│   ├── components/
│   │   ├── header.css
│   │   └── footer.css
│   └── pages/
│       ├── home.css
│       ├── about.css
│       ├── projects.css
│       └── contact.css
├── index.html
├── about.html
├── projects.html
└── contact.html
```

---

## 🛠 Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic page markup |
| **CSS3** | Styling, layout (Flexbox/Grid) and responsive design |
| **Git** | Version control |
| **GitHub** | Repository hosting and pull request management |

Design tools & visual references:
- **Figma** — prototyping and design
- **Dribbble** — visual inspiration
- **shadcn/ui** — UI component reference
- **Claude AI** — development support

---

## 🌿 Git Workflow

The project adopted a structured branching model to allow each team member to work independently on their own section, minimising merge conflicts.

```
main
 └── dev                   ← integration & code cleanup branch
      ├── page/home
      ├── page/about
      ├── page/projects
      └── page/contact
```

**Workflow:**

1. Each team member worked on their own `page/pagename` branch
2. Once the page was complete, a **pull request** was opened into `dev`
3. On the `dev` branch, the team reviewed, integrated and cleaned up the code
4. Once stable, `dev` was merged into `main` for release

---

## 🎨 CSS Architecture

To ensure visual consistency across the site while keeping files separate (and therefore avoiding merge conflicts), the following strategy was adopted:

- **`css/base.css`** — contains all **global CSS variables** (colors, fonts, spacing, breakpoints), the reset and shared base styles. This file is imported in every page.
- **`css/components/`** — styles for reusable components such as header and footer.
- **`css/pages/`** — each page has its own **dedicated CSS file**, worked on independently by the team member responsible for that section.

This approach allowed every developer to implement the **responsive design** of their own page without interfering with anyone else's work.

---

## 📄 Pages

| Page | HTML File | CSS |
|---|---|---|
| Home | `index.html` | `css/pages/home.css` |
| About | `about.html` | `css/pages/about.css` |
| Projects | `projects.html` | `css/pages/projects.css` |
| Contact | `contact.html` | `css/pages/contact.css` |

---

## 👥 Team

Project developed as a team as part of a Web Design course/project.

| Name | Role | GitHub |
|---|---|---|
| Francesco | Home, Contact, Responsive & Git/GitHub versioning | [@francescoGemolo](https://github.com/francescoGemolo) |
| Daniele | Header, Footer, About & Responsive | [@DanieleLG90](https://github.com/DanieleLG90) |
| Paula | Figma Design, Projects & Responsive | [@PaulaBCdev](https://github.com/PaulaBCdev) |
