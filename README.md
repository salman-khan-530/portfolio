# Salman Masood — Modern AI/ML Portfolio Website

A modern, responsive, and minimalist developer portfolio built for **Salman Masood** (AI/ML Intern & Computer Science (AI) Student).

![Portfolio Preview](https://img.shields.io/badge/Status-Live%20Ready-success?style=for-the-badge)
![Tech Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20TailwindCSS%20%7C%20JS-blue?style=for-the-badge)

---

## 🌟 Highlights & Features

- **Design Aesthetic:** Modern, minimalist tech theme with ambient background glow and subtle glassmorphic styling.
- **Dark & Light Mode:** Seamless toggle with user preference persistence via `localStorage` (defaults to dark mode).
- **Responsive Layout:** 100% mobile, tablet, and desktop friendly with a responsive mobile navigation drawer.
- **Live Project Showcases:**
  - **AI Voice Assistant:** Links directly to your live [Streamlit Deployment](https://salman-ai-voice-assistant-nwbn7vg4wdu9wvbr2ueqej.streamlit.app/).
  - **E-Commerce Product Scraper:** Links directly to your live [Vercel App](https://web-scraping-project-using-react-6q.vercel.app/).
- **Interactive Features:**
  - One-click **Copy Email** button with feedback indicator.
  - Interactive **Quick Contact Form** generating pre-filled direct `mailto:` links.
  - Interactive Python-style terminal card showcasing your skill profile.
  - Direct links to **GitHub** (`salman-khan-530`) and **LinkedIn** (`salman-masood1`).

---

## 🚀 How to Run Locally

Because this project is built using modern standalone HTML5, Tailwind CSS CDN, and vanilla JavaScript, **no build tools or Node.js installations are required**.

1. Navigate to the project folder:
   ```bash
   C:\Users\Lenovo\.gemini\antigravity\scratch\portfolio-salman-masood\
   ```
2. Double-click **`index.html`** or right-click and choose **"Open with Google Chrome"** (or Edge/Brave/Firefox).
3. The portfolio will launch instantly in your browser!

---

## 🌐 How to Deploy for Free (In Under 2 Minutes)

### Option 1: GitHub Pages (Recommended)
1. Create a new repository on your GitHub account ([github.com/salman-khan-530](https://github.com/salman-khan-530)) named `salman-khan-530.github.io` (or `portfolio`).
2. Push or upload `index.html` to the repository.
3. Go to **Settings** > **Pages** > Select branch `main` and root `/` > Click **Save**.
4. Your website will be live at `https://salman-khan-530.github.io`!

### Option 2: Netlify Drop (Zero Setup)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop the `portfolio-salman-masood` folder directly onto the browser window.
3. Your site will instantly go live with an HTTPS URL.

### Option 3: Vercel
1. Run `npx vercel` inside this folder or import your GitHub repository into [Vercel](https://vercel.com).

---

## ✏️ Customization & Updating Content

- **Adding a Resume PDF:**
  Drop your resume PDF (e.g. `salman_masood_resume.pdf`) into this folder and link it in the hero or navbar section:
  ```html
  <a href="./salman_masood_resume.pdf" target="_blank" download class="...">Download CV</a>
  ```
- **Adding New Projects:**
  Duplicate one of the project cards in the `<section id="projects">` block and update the title, tags, description, and links.
