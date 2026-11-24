# Shatabdee Paul — Portfolio

A personal portfolio highlighting my computer science studies, interests in backend engineering, and selected software projects.

**Live site:** [pritom099.github.io/Portfolio](https://pritom099.github.io/Portfolio/)

## Features

- Responsive layout for desktop, tablet, and mobile
- Profile photo and introductory hero section
- Project cards with category filters
- About, technical skills, and build approach sections
- Mobile navigation and accessible in-page links
- GitHub Pages deployment through GitHub Actions

## Featured projects

- **Distributed KV Store** — a Go key-value store exploring Raft consensus and fault tolerance
- **Compiler Frontend** — a C++ lexer and parser that generates abstract syntax trees
- **Daily Task Tracker** — a small browser-based to-do list built with HTML, CSS, and JavaScript

## Built with

- HTML
- CSS
- JavaScript

## Run locally

No build tools or package installation are required. Clone the repository and open `index.html` in a browser.

```bash
git clone https://github.com/Pritom099/Portfolio.git
cd Portfolio
```

## Deployment

The workflow at `.github/workflows/pages.yml` deploys the site to GitHub Pages when changes are pushed to `main`.

## Project structure

```text
.
├── .github/workflows/pages.yml
├── images/shatabdee-profile.jpeg
├── index.html
├── README.md
└── style.css
```

## Customization

Update the project details, contact address, and social links in `index.html`. Replace `images/shatabdee-profile.jpeg` to use a different profile photo.
