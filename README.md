# Harshita Sharma — Portfolio

A single-page, responsive portfolio website built with plain HTML, CSS, and JavaScript.

## 🗂 Project structure

```
portfolio/
├── index.html          # Main page markup
├── css/
│   └── style.css        # All styles (design tokens, layout, components)
├── js/
│   └── main.js           # Smooth-scroll navigation behavior
├── assets/               # (optional) put images/resume PDF here
└── README.md
```

## 🚀 Running locally

No build step is required — it's plain HTML/CSS/JS.

**Option 1 — Just open it:**
Double-click `index.html`, or open it in your browser directly.

**Option 2 — VS Code Live Server (recommended):**
1. Open the `portfolio` folder in VS Code.
2. Install the **Live Server** extension (if you don't have it).
3. Right-click `index.html` → **Open with Live Server**.

**Option 3 — Quick local server via Node:**
```bash
npx serve .
```

## 📦 Deploying / pushing to GitHub

```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/Harshita6097/<your-repo-name>.git
git push -u origin main
```

### Free hosting options
- **GitHub Pages**: In your repo, go to Settings → Pages → set source to `main` branch, `/root`. Your site will be live at `https://harshita6097.github.io/<repo-name>/`.
- **Vercel / Netlify**: Import the GitHub repo and deploy — zero config needed for a static site.

## ✏️ Customizing

- **Colors / fonts / spacing** — edit the `:root` CSS variables at the top of `css/style.css`.
- **Content** — edit the text directly inside `index.html` (About, Skills, Experience, Projects, Certifications, Contact sections are clearly commented).
- **Add a project** — copy a `.proj-card` block inside the `#projects` section and update its contents.
- **Resume download** — drop a PDF into `assets/`, then add a link/button pointing to `assets/resume.pdf`.

## 🛠 Built with

- HTML5 / CSS3 (custom properties, CSS Grid & Flexbox)
- Vanilla JavaScript (no frameworks, no build tools)
- Google Fonts: Space Grotesk, Manrope, IBM Plex Mono
