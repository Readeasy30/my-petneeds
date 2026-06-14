# My Pet Needs — Project Context for Claude

## Project Overview
- **Site:** MyPetNeeds / petneeds.ai — pet care content and resource site
- **Tech Stack:** Vanilla HTML + CSS (single `styles.css`), no build step
- **Deployment:** Cloudflare Pages, connected to this GitHub repo (`main` auto-deploys)
- **Cloudflare Worker:** `my-petneeds` worker deployed for backend logic
- **Domain:** petneeds.ai (Cloudflare managed)

## Project Structure
- `index.html` — homepage
- `styles.css` — single global stylesheet (mobile-first)
- `upload-photo.html` + `upload-photo/` — pet photo upload feature
- `starter-guides.html` — guide index page
- `ask-ai.html` — AI pet Q&A page
- `emergency.html` — pet emergency resources
- **Pet category pages:** `dogs.html`, `cats.html`, `birds.html`, `fish.html`, `reptiles.html`, `small-pets.html`, `senior-pets.html`, `rescue.html`
- **Content pages:** checklists, care guides, how-to articles (50+ HTML files)
- **Trust/legal pages:** `about.html`, `contact.html`, `privacy.html`, `terms.html`, `advertise.html`, `affiliate-disclosure.html`
- `404.html` — custom error page
- `_headers` — Cloudflare Pages security headers
- `_redirects` — Cloudflare Pages URL redirects
- `sitemap.xml`, `robots.txt` — SEO files
- `DEPLOY-TRIGGER.txt` (if present) — bump to force Cloudflare Pages redeploy

## Important Rules
- **No frameworks** — pure HTML/CSS only, no JavaScript frameworks
- **No unsupported veterinary or medical claims** — always include disclaimers
- **Mobile-first** — test all pages on mobile before deploying
- **No live monetization, tracking pixels, or private keys** without approval
- **No external service dependencies** added without approval
- Keep content helpful, accurate, and pet-owner friendly

## Git Workflow
- `main` branch auto-deploys to Cloudflare Pages
- Feature branches: `feature/branch-name` or `claude/...`
- Follow Conventional Commits: `feat:`, `fix:`, `chore:`, `docs:`
- To force redeploy: update `DEPLOY-TRIGGER.txt` with a timestamp

## SEO & Content Guidelines
- All pages must have `<title>`, `<meta description>`, and canonical URL
- Use structured, crawlable HTML — no JS-rendered content
- Sitemap and robots.txt must stay up to date when adding new pages
- No unsupported health/medical claims about pets
