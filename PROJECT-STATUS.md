# PetNeeds.ai Project Status

Date updated: 2026-05-28

## Current status

PetNeeds.ai is a simple static pet information and community website.

The repo uses plain HTML, plain CSS, and optional plain JavaScript.

## Codex-first workflow

Codex is the primary workflow for routine PetNeeds.ai repository editing.

The ChatGPT GitHub connector should be used only for small reads, checks, reviews, or emergency single-file edits when Codex is unavailable.

Reason: connector write-action labels like `create_file` or `update_file` can confuse the owner and slow the workflow.

Current workflow file:

- `CODEX-WORKFLOW.md`

## Current stack

- Plain HTML files
- Plain CSS in `styles.css`
- Optional plain JavaScript in `ask.js`
- GitHub repository workflow
- No React, Vite, Next.js, TypeScript, npm, or build tooling

## Site purpose

PetNeeds.ai provides family-friendly educational pet guidance for dogs, cats, fish, birds, reptiles, small pets, senior pets, rescue pets, and emergency awareness.

The site is educational only and is not a substitute for licensed veterinary care.

## What is working

- Repository has a clear README.
- Repository has AGENTS.md direct file-work rules.
- Static simple-stack direction is documented.
- Pet safety and no-diagnosis boundaries are documented.

## Production rules still active

- Keep current simple stack.
- Do not add private keys.
- Do not add payment setup yet.
- Do not add live ads yet.
- Do not add tracking yet.
- Do not delete major working code.
- Do not make veterinary diagnosis claims.
- Commit useful safe changes directly.

## Safe build priorities

1. Keep navigation simple and consistent.
2. Keep support pages available: About, Contact, Privacy, Terms, and Affiliate Disclosure.
3. Add useful pet content pages gradually.
4. Improve mobile layout and accessibility basics.
5. Keep all content beginner-friendly and family-safe.
6. Avoid live ads, payment handling, private keys, and medical diagnosis claims until intentionally configured.
7. Add local ad and affiliate planning only as documentation until privacy and trust rules are ready.

## Blockers

None right now.

## Next safe queue

1. Read `AGENT-INSTRUCTIONS.md` if present.
2. Check current public pages and file map.
3. Verify homepage title, meta description, navigation, footer, robots.txt, and sitemap.xml.
4. Add or update missing launch/checklist documents if needed.
5. Add one useful pet category page only if it fits the current site structure.
6. Keep medical guidance educational and veterinarian-safe.
