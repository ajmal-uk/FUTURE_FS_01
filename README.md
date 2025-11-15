# FUTURE_FS_01: Personal Professional Portfolio

![Future Interns Logo](https://futureinterns.com/logo.png)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/TR/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-121212?style=for-the-badge&logo=github&logoColor=white)](https://pages.github.com/)

## Overview

Welcome to my public GitHub repository for **Task 1** of the **Full Stack Web Development Internship** under the **Fellowship Program** at **Future Interns**. This repo documents my progress and implementation for building a personal professional portfolio website, showcasing my journey as a Computer Science graduate and MCA student with hands-on experience in AI chatbots, mobile apps, and full-stack development.

**Intern Details**:
- **Name**: Muhammed Ajmal U K
- **Track Code**: FS (Full Stack Web Development)
- **Offer ID**: FIT/NOV25/FS7463
- **Internship Period**: November 15, 2025 – December 15, 2025
- **Program Guidelines**:
  - Self-paced, self-directed learning with no formal training.
  - Minimum 2 tasks for Completion Certificate; 3 for Letter of Recommendation (LoR).
  - Public repo naming: `FUTURE_FS_TaskNumber`.
  - Mandatory LinkedIn posts after each task completion.
  - Deployment recommended for real-world showcase.

This project is a single-page, responsive portfolio site built entirely with vanilla **HTML5, CSS3, and JavaScript** (no frameworks). The contact form uses **Google Apps Script** for serverless submissions, logging data to a Google Sheet for easy notifications. It's designed to highlight my skills in prompt engineering, API integration, data analysis, and full-stack tools like Python, Flutter, and Firebase.

**Internship Offer Letter**: [View PDF](Offer_Letter.pdf)

**My Resume**: [View PDF](My_Resume.pdf)

## Project Description

As per Task 1 guidelines:
- **Task**: Create a personal portfolio website showcasing skills, projects, and achievements.
- **Key Features Implemented**:
  - Interactive resume & portfolio sections (smooth scrolling navigation, animated skill progress bars via JS).
  - Contact form with submission handling (data appended to Google Sheet; optional email alerts configurable).
  - SEO optimization (semantic HTML, meta tags, responsive design, alt attributes for images).
- **Why This Stack?**: Emphasizes core web fundamentals for a lightweight, accessible site. Integrates serverless form handling to demonstrate practical full-stack thinking without a traditional backend.

This portfolio reflects my background: Building privacy-first AI chatbots (e.g., Byte AI) and travel-matching apps (e.g., Explore Together), with a focus on LLM integration and cloud deployments.

## Tech Stack

| Category       | Technologies/Tools                  |
|----------------|-------------------------------------|
| **Frontend**   | HTML5, CSS3, Vanilla JavaScript    |
| **Form Handling** | Google Apps Script (Google Sheets integration) |
| **Styling**    | CSS Grid, Flexbox, Media Queries (responsive) |
| **Deployment** | GitHub Pages / Netlify (static hosting) |
| **Other**      | Intersection Observer API (animations), Fetch API (form submission) |

## Features Demo

- **Live Demo**: [View Portfolio](https://ajmaluk.netlify.app) <!-- Or your GitHub Pages URL: https://ajmal-uk.github.io/FUTURE_FS_01/ -->
- **Screenshots**:
  ![Homepage](screenshots/homepage.png)
  ![Skills Section](screenshots/skills.png)
  ![Projects](screenshots/projects.png)
  ![Contact Form](screenshots/contact.png)
  ![Mobile View](screenshots/mobile.png)

### Video Walkthrough
- [Short Demo Video](screenshots/portfolio-demo.mp4) <!-- Upload to /screenshots/ for GitHub; ideal for LinkedIn post -->

## How to Run Locally

1. **Clone the Repo**:
   ```
   git clone https://github.com/ajmal-uk/FUTURE_FS_01.git
   cd FUTURE_FS_01
   ```

2. **Setup Contact Form (One-Time)**:
   - Create a Google Sheet named "Portfolio Contacts" with headers: `Timestamp | Name | Email | Message`.
   - Follow the Google Apps Script guide in [SETUP.md](SETUP.md) to deploy the script.
   - Replace `YOUR_SCRIPT_ID` in `script.js` with your deployed Web App URL.

3. **Open in Browser**:
   - Double-click `index.html` to open in your default browser.
   - Test navigation, animations, and form submission (verify data in your Google Sheet).

4. **Deploy (Recommended)**:
   - **GitHub Pages**: Repo Settings > Pages > Source: Deploy from branch `main`.
   - **Netlify**: Drag folder to [netlify.com/drop](https://netlify.com/drop).
   - Update the "Live Demo" link after deployment.

No build tools or servers required—pure static files!

## Project Structure

```
FUTURE_FS_01/
├── README.md                 # This file: Overview, setup, and documentation
├── SETUP.md                  # Google Apps Script setup instructions
├── Offer_Letter.pdf          # Internship offer letter
├── My_Resume.pdf             # Personal resume for context
├── index.html                # Main portfolio page (with real projects/skills from resume)
├── styles.css                # Responsive CSS styles
├── script.js                 # JavaScript for interactions and form handling
├── screenshots/              # Visual assets for demos/LinkedIn
│   ├── homepage.png
│   ├── skills.png
│   ├── projects.png
│   ├── contact.png
│   ├── mobile.png
│   └── portfolio-demo.mp4
└── images/                   # Static assets
    ├── profile.jpg           # Your profile photo
    ├── explore-together.jpg  # Project thumbnails (e.g., from Explore Together)
    ├── byte-ai.jpg
    ├── dementia-assistant.jpg
    └── logo.png              # Favicon/personal logo
```

## Learnings & Challenges

- **Key Takeaways**:
  - Refined vanilla JS for dynamic elements like scroll-triggered animations, aligning with my JS/SQL skills from resume projects.
  - Enhanced responsive design using CSS Grid—mirrors state management in Flutter apps like Explore Together.
  - Serverless integration: Google Apps Script enables form persistence, similar to Firebase Realtime DB in my Dementia Assistant project.
  - SEO practices: Semantic markup boosts visibility, complementing my data analytics experience from Deloitte internship.

- **Challenges Overcome**:
  - Scroll animations: Leveraged `IntersectionObserver` for efficiency, avoiding performance hits on mobile.
  - Form async handling: Implemented Fetch with JSON for robust error feedback, drawing from API integration in Byte AI.
  - Personalization: Integrated real projects (e.g., GitHub links to Explore Together) for authenticity.

Resources Used (Self-Directed):
- MDN Web Docs (JS APIs).
- CSS-Tricks (Grid/Flexbox).
- Google Apps Script Docs.

## Professional Updates

- **LinkedIn Announcement**: Posted offer letter to announce my Future Interns journey. [View Post](https://www.linkedin.com/in/ajmal-uk/posts/offer-letter) <!-- Update with actual URL -->
- **Task 1 Completion Post**: Detailing the portfolio build, key learnings, and demo video. [View Post](https://www.linkedin.com/in/ajmal-uk/posts/task1-portfolio) <!-- Create and link -->
- **Profile Updates**:
  - Headline: "MCA Student | Full Stack Web Dev Intern @ Future Interns | AI/ML Enthusiast | Flutter & Python Developer"
  - Experience: Added "Intern at Future Interns" (Nov 2025 – Present), alongside Deloitte and projects.

## Next Steps in Internship

| Task | Description | Status | Repo Link |
|------|-------------|--------|-----------|
| **Task 1** | Personal Portfolio | ✅ Completed | [This Repo](https://github.com/ajmal-uk/FUTURE_FS_01) |
| **Task 2** | Mini E-Commerce Storefront | ⏳ Planned | [FUTURE_FS_02](https://github.com/ajmal-uk/FUTURE_FS_02) (TBD) |
| **Task 3** | Rebrand Famous Brand Website with AI | ⏳ Planned | [FUTURE_FS_03](https://github.com/ajmal-uk/FUTURE_FS_03) (TBD) |

Timeline (as per Program):
- Submission Form: ~November 30, 2025
- Certificate & LoR: ~December 20, 2025
- Goodies Access: Post-Completion ($100 worth)

## Contact & Connect

Seeking SDE/ML Engineering internships—let's connect on full-stack or AI projects!

- **Email**: [ajmaluk.me@gmail.com](mailto:ajmaluk.me@gmail.com)
- **Phone**: +91 8547197122
- **LinkedIn**: [Muhammed Ajmal U K](https://www.linkedin.com/in/ajmal-uk)
- **GitHub**: [ajmal-uk](https://github.com/ajmal-uk)
- **Portfolio**: [ajmaluk.netlify.app](https://ajmaluk.netlify.app)

## Acknowledgments

- **Future Interns**: Thankful for this skill-building opportunity. [Website](https://futureinterns.com) | [LinkedIn](https://linkedin.com/company/future-interns) | [Email](mailto:contact@futureinterns.com)
- **Inspirations**: My projects like Byte AI and certifications (e.g., Oracle OCI AI Foundations) fueled this build.

---

*Last Updated: November 15, 2025*  
*Built with vanilla web tech to showcase full-stack fundamentals. PRs welcome!*  
*🚀 Aiming for LoR—excited for Tasks 2 & 3!*