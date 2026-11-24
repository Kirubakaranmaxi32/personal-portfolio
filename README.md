# Personal Portfolio Website - M. Kirubakaran

> **NeuroTech Solutions – Web Development Internship | Task 1**  
> Professional Four-Page Engineering Portfolio built strictly with **HTML5 and CSS3** (No frameworks, No JavaScript).

---

## 📑 Project Overview

This repository contains the complete source code for the professional personal portfolio website of **M. Kirubakaran**, developed as part of the official Web Development Internship curriculum at **NeuroTech Solutions**.

Designed from the ground up to reflect a minimalist, elegant, and modern software engineering aesthetic, the website adheres strictly to vanilla **HTML5** and **CSS3** specifications. It demonstrates production-level proficiency in responsive layouts, **CSS Flexbox**, **CSS Grid**, media queries, typography, accessible semantic markup, and cross-device design.

---

## 👨‍💻 Developer Information

- **Full Name:** M. Kirubakaran
- **Professional Display Name:** KIRUBAKARAN
- **Professional Identity:** Aspiring Software Engineer | AI & Data Science Student
- **Education:** B.Tech – Artificial Intelligence and Data Science (AI & DS)
- **Institution:** Kangeyam Institute of Technology
- **Location:** Erode, Tamil Nadu, India
- **Email:** [mkirubakaranmohanrajj2013@gmail.com](mailto:mkirubakaranmohanrajj2013@gmail.com)
- **GitHub:** [https://github.com/kirubakaran-ai24](https://github.com/kirubakaran-ai24)
- **LinkedIn:** [https://www.linkedin.com/in/kirubakaran-m32/](https://www.linkedin.com/in/kirubakaran-m32/)
- **LeetCode:** [https://leetcode.com/u/mkirubakaran20/](https://leetcode.com/u/mkirubakaran20/)

---

## 🛠️ Technologies Used

- **HTML5:** Semantic elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<figure>`), native form validation, accessible labels, and meta tags.
- **CSS3:** Custom properties (CSS variables), modern resets, fluid typography using `clamp()`, and transitions.
- **CSS Flexbox:** Applied for navigation bars, hero content alignment, badge groupings, button rows, and footers.
- **CSS Grid:** Multi-column capability grids, skills categorization, project card grids, and two-column contact layouts.
- **CSS Media Queries:** Responsive breakpoints for large screens (≥1024px), laptops (1024px), tablets (768px–1023px), and mobile devices (<768px down to 360px).
- **Pure CSS Architecture:** Zero external CSS libraries (No Bootstrap, No Tailwind) and Zero JavaScript (No React, No Vue, No jQuery).

---

## 🎨 Design System & Palette

The website follows an engineered dark theme built around high-contrast, accessibility-tested color tokens:

| Token | Hex Code | Purpose |
| :--- | :--- | :--- |
| **Primary Background** | `#0B1120` | Base canvas background for dark aesthetics |
| **Secondary Background** | `#111827` | Alternating section background and mobile menu container |
| **Card Background** | `#172033` | Elevated surface for project cards, skills, and contact panels |
| **Card Hover** | `#1E293B` | Interactive state for cards and focus blocks |
| **Accent Color** | `#60A5FA` | Electric blue highlighting brand, icons, tags, and active states |
| **Primary Text** | `#F8FAFC` | High-contrast body and heading text (WCAG AAA compliant) |
| **Secondary Text** | `#94A3B8` | Subtle supportive and descriptive text |
| **Border Color** | `#263449` | Subtle geometric dividers and card outlines |

---

## 📂 Project Structure

```
personal-portfolio/
│
├── index.html          # Page 1: Home / Landing Page
├── about.html          # Page 2: About Me, Education & Skills
├── projects.html       # Page 3: Technical Project Showcase
├── contact.html        # Page 4: Contact Channels & Form
│
├── css/
│   └── style.css       # Unified modular CSS3 stylesheet (Zero inline styles)
│
├── images/
│   ├── profile.jpeg    # Authentic professional portrait photograph
│   ├── profile.jpg     # Preserved photograph link
│   └── projects/       # Projects directory (clean CSS card presentation)
│
└── README.md           # Comprehensive project documentation
```

---

## 📄 Four-Page Architectural Breakdown

### 1. Home Page (`index.html`)
- **Hero Section:** Features greeting, full name, dual professional titles, and verified introductory bio.
- **Call-to-Action:** Primary button navigating to `projects.html` and secondary button navigating to `contact.html`.
- **Profile Image Area:** Renders Kirubakaran's authentic portrait photograph with clean, responsive aspect-ratio framing.
- **Technical Skills Preview:** Immediate visual tags highlighting Python, HTML5, CSS3, SQL, NumPy, Pandas, and Machine Learning.
- **Philosophy Highlights:** Three-card CSS grid illustrating Software Engineering, AI & Data Science, and Practical Problem Solving.
- **Social Profile Links:** Direct external anchors to GitHub, LinkedIn, and LeetCode.

### 2. About Page (`about.html`)
- **Section A (About Me):** Verified academic focus narrative outlining programming, data analysis, and career ambitions.
- **Section B (Education):** Details B.Tech in Artificial Intelligence and Data Science at Kangeyam Institute of Technology, Tamil Nadu, India.
- **Section C (Technical Skills):** Structured categorization across Programming (Python, C), Frontend (HTML5, CSS3), Data Science (NumPy, Pandas, SQL), Analytics (Power BI), AI/ML fundamentals, and Developer Tools (Git, GitHub).
- **Section D (Professional Interests):** Seven-point grid covering Software Engineering, AI, ML, Data Science, Cybersecurity, Backend Development, and Problem Solving.

### 3. Projects Page (`projects.html`)
- **Project 01 — AI Skill Matching:** Full-stack collaborative AI platform matching users via PyTorch, Sentence Transformers, FastAPI, and React.
- **Project 02 — HRMS Talent and Performance Management:** Collaborative internship module at Cube AI Solutions. Marked honestly as *Technologies: Under development*.
- **Project 03 — Personal Portfolio Website:** The responsive four-page website developed strictly with HTML5 and CSS3.
- **Integrity Compliance:** No invented repository links or deceptive deployment buttons; unavailable features clearly display *Coming Soon*.

### 4. Contact Page (`contact.html`)
- **Channels:** Direct verified email address (`mkirubakaranmohanrajj2013@gmail.com`), location (Erode, Tamil Nadu, India), and social profiles.
- **Contact Form:** Semantic form containing Full Name, Email Address, Subject, and Message with HTML5 `required` validation and accessible label pairings.
- **Static Notice:** Transparent disclaimer notifying users of the static frontend nature of the page.

---

## 📱 Responsive Design & Breakpoints

The responsive layout employs fluid measurements (`clamp()`, percentages, `rem`) and tested media query ranges:

1. **Desktop Screens (≥ 1024px):** Full multi-column grids, horizontal navigation bar, expanded hero layout with side-by-side text and portrait card.
2. **Tablets (768px – 1023px):** Two-column card grids, balanced spacing, optimized font scales.
3. **Mobile Devices (< 768px, tested down to 360px & 390px):**
   - Single-column flow with zero horizontal overflow.
   - Pure CSS responsive navigation menu using an accessible checkbox toggle (`#nav-toggle`).
   - Touch-optimized interactive targets (minimum 44×44px tap areas).
   - Stacked full-width action buttons and form inputs.

---

## ⚠️ Contact Form Technical Limitation

> **Important Architectural Disclosure:**  
> This project is engineered exclusively with **HTML5 and CSS3** in accordance with strict internship guidelines prohibiting server runtimes (Node.js, PHP, Python backends).  
> In pure HTML/CSS, form submission cannot directly dispatch emails or persist messages to a database.  
> 
> To enable live production email delivery:
> 1. Connect the form `action` attribute to an external service like [Formspree](https://formspree.io) (`action="https://formspree.io/f/your_form_id"`), [EmailJS](https://www.emailjs.com), or [Web3Forms](https://web3forms.com).
> 2. Or implement a backend handler using FastAPI / Node.js.

---

## 🚀 Running the Project Locally

No package managers, build steps, or compilers are required.

### Method 1: Direct File Opening
Double-click `index.html` inside the `personal-portfolio` folder to open it in any web browser (Chrome, Edge, Firefox, Safari).

### Method 2: Local HTTP Server (Recommended)
Using Python (built into macOS/Linux and Windows):
```bash
# Navigate to the personal-portfolio folder
cd personal-portfolio

# Start a lightweight local server
python -m http.server 8000
```
Open your browser and navigate to:
```
http://localhost:8000
```

---

## 🌐 GitHub Repository & GitHub Pages Deployment Guide

Follow these step-by-step instructions to push this portfolio to GitHub and publish it live for free via GitHub Pages.

### Step 1: Create a New GitHub Repository
1. Log in to your GitHub account: [https://github.com/kirubakaran-ai24](https://github.com/kirubakaran-ai24).
2. Click the **+** icon in the top right corner and select **New repository**.
3. Repository name: `personal-portfolio` (or `portfolio`).
4. Visibility: Select **Public**.
5. Leave "Initialize this repository with a README" **unchecked** (we already have a complete README).
6. Click **Create repository**.

### Step 2: Initialize Git and Commit Locally
Open your terminal (PowerShell or Bash) and run:
```bash
# 1. Navigate to your project folder
cd "c:\Users\kirubakaran\Desktop\PORTFOLIO\personal-portfolio"

# 2. Initialize git repository
git init

# 3. Add all files to staging
git add .

# 4. Create your initial commit
git commit -m "feat: complete professional 4-page portfolio website for NeuroTech Solutions internship"

# 5. Rename branch to main
git branch -M main

# 6. Link to your GitHub remote repository (replace with your repo URL)
git remote add origin https://github.com/kirubakaran-ai24/personal-portfolio.git

# 7. Push code to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. On GitHub, navigate to your repository page (`https://github.com/kirubakaran-ai24/personal-portfolio`).
2. Click the **Settings** tab (gear icon at the top).
3. On the left sidebar under the "Code and automation" section, click **Pages**.
4. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
5. Under **Branch**, select `main` from the dropdown and leave the folder as `/ (root)`.
6. Click **Save**.

### Step 4: Access Your Live Website URL
1. Wait 1 to 2 minutes for the GitHub Actions deployment workflow to finish.
2. Refresh the GitHub Pages settings page. You will see a banner:  
   *“Your site is live at `https://kirubakaran-ai24.github.io/personal-portfolio/`”*
3. Test your live website in any desktop and mobile browser.

---

## ⚖️ License & Attribution

Developed by **M. Kirubakaran** as an official internship deliverable for **NeuroTech Solutions**.  
All design patterns, semantic markup, and styling are engineered for high maintainability, performance, and accessibility.
