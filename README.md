# Full Stack Web Development Internship - Task 1: Personal Portfolio

**Muhammed Ajmal U K**

A sleek, responsive, dark-themed portfolio website highlighting my skills, projects, and professional background. Built as part of the Future Interns Fellowship Program.

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fajmal-uk.github.io%2FFUTURE_FS_01&style=flat-square&logo=google-chrome&labelColor=1a1a1a&color=00b4b4)](https://ajmal-uk.github.io/FUTURE_FS_01)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![GitHub Repo stars](https://img.shields.io/github/stars/ajmal-uk/FUTURE_FS_01?style=flat-square&logo=github)](https://github.com/ajmal-uk/FUTURE_FS_01/stargazers)

**Live Demo:** [ajmal-uk.github.io/FUTURE_FS_01](https://ajmal-uk.github.io/FUTURE_FS_01) *(deploy and update this link accordingly)*

---

## About the Internship

This project is Task 1 for the **Full Stack Web Development Internship** under the Future Interns Fellowship Program (Track Code: FS). Future Interns is an ISO-certified, MSME-recognized platform offering remote, self-paced internships to students and young professionals worldwide. With over 10,000 participants from 50+ countries, the program emphasizes hands-on projects, skill-building, and career readiness—without fixed schedules or formal training.

**Key Program Details:**
- **Duration:** 1 month (November 15, 2025 – December 15, 2025, as per my offer letter).
- **Structure:** Self-directed with 3 tasks; complete at least 2 for a Completion Certificate, 3 for a Letter of Recommendation (LoR).
- **Benefits:** Real-world experience, verified certificates (optional government-recognized for a fee), access to a premium community for job alerts and networking, and $100 worth of goodies upon completion.
- **Guidelines:** Maintain public GitHub repos (e.g., "FUTURE_FS_01"), submit via mid-month form, post updates on LinkedIn (mandatory after each task), and focus on domain-specific work.
- **Timeline:** Offer letter received → Tasks & submissions → Certificate/LoR processed.

For verification:
- **Offer Letter:** [`assets/docs/MUHAMMED_AJMAL_U_K_Offer_Letter.pdf`](./assets/docs/MUHAMMED_AJMAL_U_K_Offer_Letter.pdf)
- **Internship Brochure:** [`assets/docs/Future_Interns_Full_Stack_Web_Development.pdf`](./assets/docs/Future_Interns_Full_Stack_Web_Development.pdf)

*Note: Move the provided PDF files to `assets/docs/` and commit them for proper linking.*

---

## Task 1 Description (from Brochure)

**Build a Personal Professional Portfolio**

- **Objective:** Create a personal portfolio website showcasing skills, projects, and achievements.
- **Recommended Tech:** 
  - Frontend: HTML, CSS, JavaScript (React.js recommended).
  - Backend: Node.js (optional for contact form & blog integration).
  - Database: MySQL / MongoDB (for project updates & contact form).
- **Key Features:**
  - Interactive resume & portfolio section.
  - Contact form with email notifications.
  - SEO optimization for better visibility.

This repo implements the above with a modern twist, including vanilla JS for interactivity and Google Apps Script for form handling.

---

### Featured Projects
These are examples of my previous work, integrated into the portfolio:

| Project       | Tech Stack                  | Live Demo                                      | Source Code |
|---------------|-----------------------------|------------------------------------------------|-------------|
| Byte AI      | Flask + OpenAI API          | [byte.pythonanywhere.com](https://byte.pythonanywhere.com) | [Private]   |
| ToolPix      | Flask + Image Processing    | [toolpix.pythonanywhere.com](https://toolpix.pythonanywhere.com) | [Private]   |
| Zymail       | Flask + Email Automation    | [zymail.pythonanywhere.com](https://zymail.pythonanywhere.com) | [Private]   |

---

## 🌟 Features

- Modern dark UI with animations, hover effects, and mobile responsiveness.
- Project gallery with tags, filters, and links to demos/source.
- Functional contact form (integrated with Google Apps Script for submissions).
- UX enhancements: Toast notifications, loading spinners, and collapsible sidebar.
- Downloadable resume (PDF).
- Optimized for SEO and accessibility (alt texts, lazy loading).
- Fast performance with minified assets.

---

## 🛠️ Tech Stack

- **Core:** HTML5, CSS3 (Flexbox/Grid), Vanilla JavaScript.
- **Icons:** Font Awesome.
- **Form Handling:** Google Apps Script.
- **Hosting (Demos):** PythonAnywhere for Flask apps.
- **Deployment:** GitHub Pages, Netlify, or Vercel recommended.

---

## 🚀 Quick Start (Local Setup)

Static site—no build required!

### Option 1: Python Server
```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

### Option 2: Node.js (with `serve`)
```bash
npx serve -s .
# Visit http://localhost:5000
```

### Option 3: Open Directly
Double-click `index.html` (note: contact form may not work due to CORS—use a server).

---

## 🚀 Deployment Guide

### GitHub Pages (Free)
1. Push to GitHub (`main` branch).
2. Settings → Pages → Source: `main` / root.
3. Live at: `https://<username>.github.io/FUTURE_FS_01`.

### Netlify/Vercel
1. Connect repo via GitHub.
2. No build command needed (static site).
3. Get HTTPS, custom domain, and auto-deploys.

---

## 📂 Project Structure
```
FUTURE_FS_01/
├── index.html          # Landing page
├── projects.html       # Projects showcase
├── assets/
│   ├── img/            # Screenshots and images
│   ├── docs/           # PDFs (offer letter, brochure)
│   └── resume.pdf      # Downloadable CV
├── css/
│   └── style.css       # Styles
└── js/
    └── main.js         # Scripts
```

*Pro Tip: Extract inline CSS/JS to these files for better organization (already suggested in improvements).*

---

## 📬 Contact & Socials

- ✉️ Email: [ajmaluk.me@gmail.com](mailto:ajmaluk.me@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/ajmal-uk](https://www.linkedin.com/in/ajmal-uk)
- 🐙 GitHub: [github.com/ajmal-uk](https://github.com/ajmal-uk)
- ☕ Buy Me a Coffee: [buymeacoffee.com/ajmal.uk](https://buymeacoffee.com/ajmal.uk)

---

## ✨ Improvements Implemented / To-Do

- [x] Use relative paths for assets (e.g., `assets/img/`).
- [x] Add `rel="noopener noreferrer"` to external links.
- [x] Implement `loading="lazy"` and `alt` attributes for images.
- [x] Add project badges in table.
- [ ] Integrate optional backend (e.g., Node.js for advanced form handling).
- [ ] Add video demo to LinkedIn post.

---

## 📝 License

MIT License—fork, modify, and use freely (attribution appreciated).

---

## 🔥 LinkedIn Post Template

```
Excited to share my Task 1 completion for the Future Interns Full Stack Web Development Internship! 🚀

Built a responsive portfolio site with HTML/CSS/JS, featuring a contact form, project gallery, and dark theme. This self-paced program is boosting my skills—grateful for the opportunity!

Live Demo: https://ajmal-uk.github.io/FUTURE_FS_01
Repo: https://github.com/ajmal-uk/FUTURE_FS_01

#FullStack #WebDevelopment #Portfolio #Internship #FutureInterns #Coding