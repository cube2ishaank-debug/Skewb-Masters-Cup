<img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/0d7d9a3b-19aa-4c6b-a989-038fdb1b8293" />

# Skewb Masters Cup

Official website for the **Skewb Masters Cup (SMC)** — the first head-to-head Skewb championship, hosted online and open globally.

A single-page site built as one self-contained `index.html` (HTML/CSS/JS, no build step, no dependencies) with client-side page routing.

## Pages

The site is a single HTML file with JS-driven view switching (`showPage()`), covering:

- **Home** — hero, event overview, and sponsor highlight
- **Our Team** — organizer/contributor bios with WCA profile and social links
- **YouTube** — featured channels from team members and contributors
- **Sponsors** — sponsor info and details
- **Resources** — competitor resources

## Project structure

```
.
├── index.html      # Entire site: markup, styles, and routing logic
└── images/         # Logos and team/contributor photos
```

## Running locally

No build tools or server-side code required. Either:

- Open `index.html` directly in a browser, or
- Serve the folder locally, e.g.:

```bash
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Vibe Coded
This website was vibecoded through the help of AI using tools such as Claude.ai & Google Antigravity.
