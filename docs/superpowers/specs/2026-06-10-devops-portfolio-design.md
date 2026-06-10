# DevOps Portfolio Design Spec

## Overview
A multi-page static portfolio website for Sahil Kulkarni, a DevOps Engineer fresher. Built with pure HTML/CSS/JS, hosted on GitHub Pages, deployed via GitHub Actions CI/CD.

## Tech Stack
- **Runtime:** None (static files)
- **Languages:** HTML5, CSS3, JavaScript (vanilla)
- **Hosting:** GitHub Pages
- **CI/CD:** GitHub Actions (auto-deploy on push to `main`)
- **Dependencies:** Zero

## Site Structure (7 pages)
| Page | File | Content |
|------|------|---------|
| Home | `index.html` | Terminal hero, typing animation, CTAs |
| About | `about.html` | Professional summary, quick info bar |
| Projects | `projects.html` | Project cards with tech tags |
| Skills | `skills.html` | Categorized skill badges |
| Certifications | `certifications.html` | Certification cards |
| Education | `education.html` | Education timeline |
| Contact | `contact.html` | Form + social links |

## Navigation
- Fixed top nav bar with glass-morphism effect
- Links to all 7 pages
- Active page highlighted with accent color
- Mobile-responsive hamburger menu

## Visual Design
- **Background:** `#0a0a0f`
- **Cards/Surfaces:** `#13131a` with `#1e1e2e` borders
- **Primary:** `#00ff88` (terminal green) with glow effects
- **Secondary:** `#0ea5e9` (cyber blue)
- **Text:** `#e2e8f0` / `#64748b`
- **Fonts:** System monospace stack
- **Effects:** CSS transitions, glow on hover, terminal cursor blink, subtle background grid pattern

## Key Features
- Terminal-style typing animation on homepage
- Project cards with expandable details
- Skill badges grouped by category
- Contact form (static, with mailto fallback)
- Smooth scrolling and fade-in animations
- Fully responsive (mobile, tablet, desktop)

## File Structure
```
portfolio/
├── index.html
├── about.html
├── projects.html
├── skills.html
├── certifications.html
├── education.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── assets/
├── .github/
│   └── workflows/
│       └── deploy.yml
└── README.md
```
