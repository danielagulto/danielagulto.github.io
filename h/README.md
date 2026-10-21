# danielagulto.github.io

Personal portfolio of Daniel Agulto — full-stack developer focused on backend and database development (Java, Spring Boot, React, TypeScript, Node.js, PHP, PostgreSQL, MySQL). Based in Madrid, Spain.

Live site: https://danielagulto.github.io

## Structure

| Path | Purpose |
|---|---|
| `index.html` | Home page: skills, selected work, experience, education, contact |
| `insureflow.html` | InsureFlow project page: architecture, status, security, testing, deployment |
| `assets/site.css` | Shared stylesheet (design tokens at the top of the file) |
| `assets/img/` | InsureFlow screenshots (WebP) and the social-share image |
| `404.html`, `robots.txt`, `sitemap.xml` | Hosting and SEO basics |

## Development

There is no build step: this is a static site served by GitHub Pages from the `main` branch (root).

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Updating InsureFlow screenshots

Screenshots show the InsureFlow frontend populated with the synthetic demo records from the project's `DemoDataSeeder`. Never publish screenshots that contain real data, credentials, or private environment values.
