# ALISHA KHAN | Personal Brand Website

**Building Intelligent Products That Ship.**
Portfolio site for ALISHA KHAN, AI Expert, AI Engineer and founder (Kot Addu, Pakistan).

Built for investors, clients, technology partners, collaborators and recruiters. Plain HTML, CSS and JavaScript, with no build step and no dependencies.

## Features
- Sections: About, Expertise, Ventures, Featured projects (filterable), Tech stack, Experience, Speaking and writing, Testimonials, Work with me, Contact
- Animated hero diagram of an AI agent loop (canvas)
- Light and dark themes with a saved toggle (dark by default)
- Responsive layout, accessible navigation, reduced-motion support
- Contact form that opens the visitor's email app
- SEO tags and JSON-LD schema

## Structure
```
.
├── index.html            # page markup
├── css/styles.css        # design tokens and styles
├── js/data.js            # all your content (edit here)
├── js/main.js            # rendering, theme, form, hero animation
├── .github/workflows/    # GitHub Pages deployment
├── .nojekyll
├── LICENSE
└── README.md
```

## Edit your content
Open `js/data.js` and replace every `[EDIT]` placeholder: ventures, projects, experience timeline, talks and articles, testimonials. In `index.html`, add your LinkedIn, GitHub, X and Calendly links in the Contact section and footer.

## Change colors
Colors are variables at the top of `css/styles.css`. Change `--accent` and `--accent2` (light and dark blocks) to restyle the whole site.

## Run locally
Open `index.html` in a browser, or serve the folder:
```bash
python3 -m http.server 8000
```
Then visit http://localhost:8000.

## Publish on GitHub Pages
```bash
git init -b main
git add .
git commit -m "Initial commit: personal website"
git remote add origin https://github.com/<your-username>/alisha-khan-website.git
git push -u origin main
```
Then in the repository go to **Settings → Pages → Source: GitHub Actions**. The included workflow deploys the site on every push to `main`.

## License
MIT, see [LICENSE](LICENSE).
