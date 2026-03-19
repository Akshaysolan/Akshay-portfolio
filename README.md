# Akshay-portfolio

# Akshay Solanke — Personal Portfolio

> A professional developer portfolio built with pure HTML, CSS, and JavaScript — featuring dark/light theme toggle, scroll animations, and a custom cursor. Deployed on Vercel.

🌐 **Live Site:** [your-portfolio.vercel.app](https://your-portfolio.vercel.app)

---

## Preview

| Dark Theme | Light Theme |
|------------|-------------|
| Deep navy background with sky-blue accents | Warm parchment background with navy accents |

---

## Features

- **Dual Theme (Dark / Light)** — Toggle switch with localStorage persistence; theme is remembered across visits
- **Custom Cursor** — Trailing ring cursor with hover-scale effect on interactive elements (desktop only)
- **Scroll Reveal Animations** — Sections animate in with staggered fade-up using IntersectionObserver
- **Active Nav Highlight** — Pill-style navbar auto-highlights the current section as you scroll
- **Hero Code Card** — Mock JSON terminal card displaying profile data with syntax highlighting
- **Featured Project Layout** — AI Legal Analyzer spans a wide card; remaining projects in a responsive 3-column grid
- **Responsive Design** — Fully mobile-friendly; nav pill collapses, grid reflows to single column on small screens
- **Zero Dependencies** — No npm, no frameworks, no build step required

---

## Sections

| # | Section | Description |
|---|---------|-------------|
| 01 | **Hero** | Name, role, bio, CTA buttons, and profile JSON code card |
| 02 | **Experience** | Quality Analyst at Cumulus System + B.E. at ICEM Pune |
| 03 | **Projects** | 6 projects with live demo links, tags, and hover effects |
| 04 | **Skills** | Categorized skill chips — Languages, AI/ML, Frameworks, Tools, Databases, QA |
| 05 | **Certifications** | 5 certifications including Hackathon 2024 trophy card |
| 06 | **Contact** | Email, phone, GitHub, LinkedIn, LeetCode, HackerRank links + contact panel |

---

## Tech Stack

```
HTML5        — Structure and semantics
CSS3         — Custom properties, Grid, Flexbox, animations, backdrop-filter
JavaScript   — Theme toggle, custom cursor, IntersectionObserver, smooth scroll
Google Fonts — Playfair Display (display) + Outfit (body) + JetBrains Mono (code)
Vercel       — Static deployment
```

---

## Project Structure

```
akshay-portfolio/
├── index.html      # Entire portfolio — all HTML, CSS, and JS in one file
└── vercel.json     # Vercel deployment config for static routing
```

---

## Getting Started

### Run Locally

No installation needed. Just open the file in a browser:

```bash
# Clone or download the repo
git clone https://github.com/your-username/akshay-portfolio.git
cd akshay-portfolio

# Open directly in browser
open index.html
# or on Windows:
start index.html
```

### Deploy to Vercel

**Option 1 — Drag & Drop (fastest)**
1. Go to [vercel.com](https://vercel.com) and log in
2. Click **Add New Project**
3. Drag and drop the `akshay-portfolio` folder
4. Click **Deploy** — live in ~30 seconds

**Option 2 — GitHub Integration (recommended)**
1. Push the folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com) → **Add New Project** → **Import Git Repository**
3. Select your repo and click **Deploy**
4. Every future `git push` auto-deploys — no manual steps needed

---

## Customization

All content lives in `index.html`. To update:

| What to change | Where to find it |
|----------------|-----------------|
| Name, bio, role | `<!-- HERO -->` section |
| Experience entries | `<!-- EXPERIENCE -->` section |
| Projects & links | `<!-- PROJECTS -->` section |
| Skills | `<!-- SKILLS -->` section |
| Certifications | `<!-- CERTIFICATIONS -->` section |
| Contact links | `<!-- CONTACT -->` section |
| Accent color (dark) | `[data-theme="dark"]` → `--accent` |
| Accent color (light) | `[data-theme="light"]` → `--accent` |

---

## Live Project Links

| Project | Link |
|---------|------|
| AI Legal Document Analyzer | [streamlit.app](https://akshaysolan-rag-langchain-streamlit-app-ha9zgb.streamlit.app/) |
| AI Video Maker | [streamlit.app](https://aivideomaker-2juhvdb5uc5fj9xnjda7uw.streamlit.app) |
| Hotel Booking App | [vercel.app](https://hotel-booking-vite.vercel.app/) |
| ShopKart | [vercel.app](https://shop-kart-dun.vercel.app/) |

---

## Contact

**Akshay Solanke**
- 📧 akshaysolan804@gmail.com
- 📞 +91 88558 78880
- 📍 Pune, Maharashtra, India

---

## License

This portfolio is open for reference and inspiration. Please do not copy it wholesale and present it as your own.

---

*Built with HTML · CSS · JS — Deployed on Vercel*