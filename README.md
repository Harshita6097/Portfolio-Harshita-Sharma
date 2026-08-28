# Harshita Sharma — Portfolio

Personal portfolio website for Harshita Sharma, a Computer Science Engineer specializing in full-stack development, applied AI/ML, and the Anthropic Claude generative AI ecosystem.

Live at: [harshita6097.github.io/Portfolio-Harshita-Sharma](https://harshita6097.github.io/Portfolio-Harshita-Sharma) *(or your Vercel URL once deployed)*

---

## Overview

A single-page, fully responsive portfolio built with plain HTML, CSS, and JavaScript — no frameworks, no build tools, no dependencies. Designed for fast load times and clean presentation across all screen sizes.

Sections covered:

- Hero — role summary and skill snapshot
- About — background, education, and current position
- Skills — languages, frameworks, AI/ML tools, and platforms
- Experience — Claude CoE Internship at ProcurAI
- Projects — AgriSense, SCAResNet, AI-Powered Job Recommendation System
- Certifications — Anthropic, NPTEL, AWS, Google, Coursera
- Contact — email, phone, LinkedIn, GitHub

---

## Project Structure

```
Portfolio/
├── index.html          # All page markup and section content
├── css/
│   └── style.css       # Design tokens, layout, and component styles
├── js/
│   └── main.js         # Smooth-scroll navigation
├── assets/             # Place images or resume PDF here
└── README.md
```

---

## Running Locally

No installation or build step required.

**Option 1 — Open directly:**
Double-click `index.html` to open it in your default browser.

**Option 2 — VS Code Live Server (recommended):**
1. Open the `Portfolio` folder in VS Code.
2. Install the Live Server extension if not already installed.
3. Right-click `index.html` and select Open with Live Server.

**Option 3 — Node quick server:**
```bash
npx serve .
```

---

## Deploying to Vercel

Vercel deploys static sites with zero configuration.

**Step 1 — Push your code to GitHub**

Ensure your latest changes are committed and pushed:
```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

**Step 2 — Import the repository on Vercel**

1. Go to [vercel.com](https://vercel.com) and sign in with your GitHub account.
2. Click **Add New > Project**.
3. Find and select the `Portfolio-Harshita-Sharma` repository.
4. Click **Import**.

**Step 3 — Configure the project**

Vercel will auto-detect this as a static site. No changes needed. Leave all settings as default:
- Framework Preset: Other
- Root Directory: `./`
- Build Command: *(leave empty)*
- Output Directory: *(leave empty)*

**Step 4 — Deploy**

Click **Deploy**. Vercel will build and publish the site in under a minute.

Your site will be live at:
```
https://portfolio-harshita-sharma.vercel.app
```
*(or a custom URL you configure in Vercel project settings)*

**Step 5 — Automatic deployments**

Every future `git push` to the `main` branch will automatically trigger a new deployment on Vercel. No manual steps needed after the initial setup.

---

## Customization

- **Colors, fonts, spacing** — edit the `:root` CSS variables at the top of `css/style.css`.
- **Content** — update text directly in `index.html`; each section is clearly commented.
- **Add a project** — duplicate a `.proj-card` block inside the `#projects` section and update its content.
- **Resume download** — place a PDF in `assets/`, then add a link pointing to `assets/resume.pdf`.

---

## Built With

- HTML5 / CSS3 — custom properties, CSS Grid, Flexbox
- Vanilla JavaScript
- Google Fonts: Space Grotesk, Manrope, IBM Plex Mono

---

## Contact

Harshita Sharma
harshitasharma3003@gmail.com
[linkedin.com/in/Harshita6097](https://linkedin.com/in/Harshita6097)
[github.com/Harshita6097](https://github.com/Harshita6097)
