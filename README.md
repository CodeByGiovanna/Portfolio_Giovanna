# Giovanna de Oliveira — Portfolio

Personal portfolio built as a single HTML file. No frameworks, no build step — open directly in the browser.

**Live:** https://codebygiov anna.github.io/Portfolio_Giovanna

---

## Stack

- HTML5 · CSS3 · Vanilla JavaScript
- Tailwind CSS (CDN)
- Google Fonts — Bodoni Moda + Plus Jakarta Sans
- GitHub REST API (for the projects gallery)

## Features

- **Landing intro** — cinematic name reveal with star field animation
- **Persistent star canvas** — white stars (dark) / graphite stars (light) across all pages
- **Custom cursor** — dot + ring with easing, expands on hover
- **3D tilt** — project cards tilt on mouse move (60 fps)
- **Project modals** — case study panel (challenge → process → result → GitHub link)
- **GitHub gallery** — fetches public repos live from the API, filters featured projects
- **Robot mascot** — eye tracking, blink, mood reactions
- **Dark / Light mode** — persisted via localStorage
- **i18n** — EN · PT · IT, instant switch without reload

## Structure

```
portfolio/
├── index.html          ← entire portfolio
├── cv/
│   └── giovanna-oliveira-cv.pdf
└── .gitignore
```

## Deploy (GitHub Pages)

1. Push this repo to GitHub
2. Settings → Pages → Source: `main` / `root`
3. Done — available at `https://codebygiov anna.github.io/Portfolio_Giovanna`

---

Made by Giovanna de Oliveira · [LinkedIn](https://www.linkedin.com/in/giovanna-oliveira-software-engineer) · [GitHub](https://github.com/CodeByGiovanna)
