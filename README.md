# Portfolio — Jaiveer Bala

Personal portfolio website hosted on GitHub Pages.

## Structure

```
portfolio/
├── index.html          # Landing page (hero, about, featured projects)
├── projects.html       # Full project grid with modal detail views
├── css/
│   └── style.css       # All styles
└── assets/
    ├── resume.pdf      # ← ADD YOUR RESUME HERE
    └── cswa-cert.pdf   # ← ADD YOUR CSWA CERT HERE
```

## Setup for GitHub Pages

1. Create a new repo named `yourusername.github.io` (or any repo name for a project page)
2. Push all files to the `main` branch
3. Go to **Settings → Pages** → set source to `main` branch, `/ (root)` folder
4. Your site will be live at `https://yourusername.github.io`

## Adding your resume and certificate

Place these two files in the `assets/` folder:
- `assets/resume.pdf`
- `assets/cswa-cert.pdf`

## Updating GitHub links

When your GitHub is ready, search for `github.com/jaiveerbala` in both HTML files and update to your actual GitHub URL. Also update the `href="#"` placeholder links on each project card to point to the real repo.

## Images

All project images are loaded directly from Google Drive using thumbnail URLs. If you want to self-host images instead, download them from Drive and place them in `assets/img/` and update the `src` attributes.
