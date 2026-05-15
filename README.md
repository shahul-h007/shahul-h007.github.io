# Shahul Portfolio

Personal portfolio website for Shahul Hameed KI, hosted with GitHub Pages.

Live site: https://shahul-h007.github.io

## Overview

This is a single-page static portfolio built with HTML, CSS, and vanilla JavaScript. It showcases projects, skills, brand concepts, social links, and contact options.

## Sections

- Hero introduction
- About
- Completed projects
- Brands and concepts
- Skills and capabilities
- YouTube channel
- Contact

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Bootstrap 5
- Bootstrap Icons
- AOS animations
- Three.js background visuals
- GitHub Pages hosting

## Project Structure

```text
.
├── index.html
├── README.md
├── .editorconfig
├── .gitattributes
└── .gitignore
```

## Local Preview

Run a simple local server from the project folder:

```bash
python -m http.server 4173 --bind 127.0.0.1
```

Then open:

```text
http://127.0.0.1:4173/
```

## Deployment

The site is deployed through GitHub Pages from the `main` branch.

After editing:

```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

GitHub Pages will redeploy automatically after the push.

## Contact Form

The current contact form opens a pre-filled email to the portfolio owner. For direct in-page sending, connect a static form backend such as Web3Forms, Formspree, or EmailJS.
