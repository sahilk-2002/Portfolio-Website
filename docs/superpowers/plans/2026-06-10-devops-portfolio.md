# DevOps Portfolio Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use subagent-driven-development (recommended) or executing-plans to implement this plan task-by-task.

**Goal:** Build a 7-page static portfolio website for Sahil Kulkarni (DevOps Engineer) deployed on GitHub Pages.

**Architecture:** Pure HTML/CSS/JS static site with shared global stylesheet and JS file. Single-page-per-file approach with a dark terminal-themed design.

**Tech Stack:** HTML5, CSS3, Vanilla JS, GitHub Pages, GitHub Actions

---

### Task 1: Project scaffolding and CSS foundation

**Files:**
- Create: `index.html`, `about.html`, `projects.html`, `skills.html`, `certifications.html`, `education.html`, `contact.html`
- Create: `css/style.css`
- Create: `js/main.js`
- Create: `.github/workflows/deploy.yml`

- [ ] **Step 1:** Create directory structure (`css/`, `js/`, `assets/`, `.github/workflows/`)
- [ ] **Step 2:** Write `css/style.css` with full dark theme (variables, nav, hero, cards, tags, buttons, contact form, responsive)
- [ ] **Step 3:** Create all 7 HTML files with shared skeleton (nav, main, footer)

### Task 2: Home page with terminal hero

**File:** `index.html`

- [ ] **Step 1:** Write hero section with typing animation container (`#typed-text`, `.typing-cursor`)
- [ ] **Step 2:** Add CTA buttons linking to Projects and Contact

### Task 3: main.js

**File:** `js/main.js`

- [ ] **Step 1:** Active nav link detection based on current page
- [ ] **Step 2:** Hamburger menu toggle for mobile
- [ ] **Step 3:** Typing effect for `#typed-text` element on home page
- [ ] **Step 4:** IntersectionObserver for fade-in animations

### Task 4: About page

**File:** `about.html`

- [ ] **Step 1:** Two-column layout - photo placeholder card + professional summary
- [ ] **Step 2:** Quick info card (location, email, phone, availability)

### Task 5: Projects page

**File:** `projects.html`

- [ ] **Step 1:** Two project cards (E-Commerce DevOps, Infrastructure Provisioning)
- [ ] **Step 2:** Tech tags per project

### Task 6: Skills page

**File:** `skills.html`

- [ ] **Step 1:** Categorized skill groups with badge-style tags (CI/CD, Containers, Cloud, IaC, Monitoring, OS, Networking, VCS)

### Task 7: Certifications page

**File:** `certifications.html`

- [ ] **Step 1:** Four certification cards (DevOps Engineer, AWS, Linux, CCNA)

### Task 8: Education page

**File:** `education.html`

- [ ] **Step 1:** Two education cards (BCA, Junior College)

### Task 9: Contact page

**File:** `contact.html`

- [ ] **Step 1:** Contact form with name, email, message fields (mailto action)
- [ ] **Step 2:** Social links (Email, LinkedIn, GitHub)

### Task 10: GitHub Actions deploy workflow

**File:** `.github/workflows/deploy.yml`

- [ ] **Step 1:** Write deploy workflow triggered on push to `main`
- [ ] **Step 2:** Use `actions/configure-pages`, `upload-pages-artifact`, `deploy-pages`

### Task 11: Final polish

- [ ] **Step 1:** Add `fade-in` class to cards/sections for scroll animation
- [ ] **Step 2:** Verify mobile responsive layout
- [ ] **Step 3:** Initialize git repo, initial commit, push to GitHub
