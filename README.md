# Your Name — Portfolio Template

A single-file, no-build portfolio site. No npm, no framework, no GitHub required — just open `index.html` in a browser, or upload the folder to any free host.

## Folder structure

```
portfolio/
├── index.html     ← everything (HTML + CSS + JS) lives in this one file
├── assets/        ← put your profile photo and resume PDF here
└── README.md      ← this file
```

## How to customize

Open `index.html` in any text editor (VS Code recommended) and:

1. **Find & replace** these placeholders throughout the file:
   - `Your Name` → your actual name
   - `your.email@example.com` → your email
   - `+00 00000 00000` → your phone number
   - `github.com/your-username`, `linkedin.com/in/your-name` → your real profile links
   - `Your City, Country` → your location

2. **Profile photo** — replace the `src` in the hero section's `<img>` tag:
   ```html
   <img src="https://placehold.co/560x680/e4e2da/5b6270?text=Profile+Photo" ...>
   ```
   with `src="assets/profile.jpg"` after adding your photo to the `assets/` folder.

3. **Resume** — drop your resume PDF into `assets/` (e.g. `assets/resume.pdf`), then update the two "Download Resume" buttons' `href="#"` to `href="assets/resume.pdf"`.

4. **Projects, Education, Experience, Certifications, Achievements, Workshops** — each is a repeated card block in the HTML (search for `project-card`, `timeline-item`, `exp-item`, `mini-card`). Copy/paste a block to add more, or delete one to remove.

5. **Contact form** — currently opens the visitor's email client via `mailto:`. To receive submissions directly without a backend, connect it to a free form service like Formspree or EmailJS and swap the `<form>`'s submit handler (see the `<script>` at the bottom of the file).

## How to host it for free (no GitHub needed)

- **Netlify Drop** — go to app.netlify.com/drop and drag the `portfolio` folder in. Instant live URL.
- **Vercel** — similar drag-and-drop deploy via vercel.com.
- **Firebase Hosting** — `firebase init hosting` then `firebase deploy` (needs Node, but is free).
- **GitHub Pages** — free even without paying, once you're ready to use Git.

## Features included

- Dark / light mode (auto-detects system preference, manual toggle)
- Fully responsive (mobile, tablet, desktop)
- Smooth scrolling + scroll-reveal animations
- Sticky nav with mobile hamburger menu
- All 12 requested sections with placeholder content
