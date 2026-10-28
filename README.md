# Gold Edwin — Static Portfolio

A responsive multi-page portfolio built with plain HTML, CSS and a tiny amount of JavaScript. No backend, build step or package installation required.

## Pages
- `index.html` — home
- `about.html` — about and approach
- `computer-science.html` — Computer Science exploration
- `automation-ai.html` — AI and workflow automation
- `creative.html` — Premiere Pro and After Effects learning
- `leadership.html` — technical production, Model UN and collaboration
- `projects.html` — projects and experiments
- `contact.html` — contact placeholders to personalise

## Preview locally
Open `index.html` in a browser. For local development, VS Code's Live Server extension is also convenient.

## Deploy to Vercel
1. Create a GitHub repository and upload the contents of this folder (the HTML files, `assets/` and this README).
2. In Vercel, choose **Add New → Project** and import the repository.
3. Since this is a plain static site, leave the framework as **Other** and use the repository root as the root directory. No build command is needed.
4. Deploy.

You can also use Vercel's CLI if installed: run `vercel` from this folder and follow the prompts.

## Before publishing
- Review all copy and remove anything you don't want public.
- The contact page currently links to goldedwinofficial@gmail.com, GitHub g0ld3lux-official, personal Instagram @g0ld3lux, and professional Instagram @g0ld3lux_official. LinkedIn is intentionally omitted; add a profile photo later if desired.
- Replace project links/placeholders with only public-safe demos or repositories.
- The site uses original CSS artwork and decorative monograms for Ambassadors College, Ota and Covenant University; these are not official logos. Add an approved personal photo later if you want one.
- Keep API keys, customer data and private business details out of the portfolio.
- The Google Fonts import requires internet; fallback fonts are defined if it is unavailable.

## Editing
Each page is a standalone HTML file. Shared styling is in `assets/styles.css`; mobile menu behaviour is in `assets/script.js`.
