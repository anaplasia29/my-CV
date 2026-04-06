# Curriculum Vitae

This repository contains my academic CV written in LaTeX and automatically deployed with GitHub Pages.

## Live CV

- Website: `https://anaplasia29.github.io/<repo-name>/`
- PDF: `https://anaplasia29.github.io/<repo-name>/cv.pdf`

> Replace `<repo-name>` with your actual GitHub repository name.

## Contents

- `main.tex` — source file for the CV
- `site/index.html` — webpage that displays the compiled CV PDF
- `.github/workflows/deploy.yml` — GitHub Actions workflow for automatic build and deployment

## Build and Deployment

This repository uses **GitHub Actions** to:

1. compile `main.tex` into PDF,
2. rename the output as `cv.pdf`,
3. deploy the rendered result to **GitHub Pages**.

Any push to the `main` branch triggers automatic rebuilding and redeployment.

## Local Compilation

To compile the CV locally:

```bash
pdflatex main.tex
