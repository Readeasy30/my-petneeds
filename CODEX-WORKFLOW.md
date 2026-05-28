# Codex Workflow

Last updated: 2026-05-28

## Purpose

Codex is the main workflow for routine PetNeeds.ai repository editing.

PetNeeds.ai must stay simple, family-friendly, pet-safe, and easy to maintain.

## Current Stack

PetNeeds.ai uses:

- plain HTML files
- plain CSS in `styles.css`
- optional plain JavaScript in `ask.js`
- GitHub repository workflow

Do not convert this project to React, Vite, Next.js, TypeScript, npm, or any build tool unless Gerry clearly requests a full rebuild later.

## Why Codex Is Primary

Codex should handle routine repo work directly because it can read the repo, make safe file edits, and commit useful changes without making Gerry manually paste, create, replace, or update files.

The ChatGPT GitHub connector may show internal write-action labels like `create_file` or `update_file`. Those labels can be confusing. Use that connector mainly for small reads, checks, reviews, or emergency single-file edits when Codex is unavailable.

## Required Read Order

Before editing, read these files when they exist:

1. `README.md`
2. `AGENTS.md`
3. `AGENT-INSTRUCTIONS.md`
4. `LOCKED-CHECKPOINT.md`
5. `FILE-MANAGEMENT.md`
6. `PROJECT-STATUS.md`
7. `CODEX-WORKFLOW.md`

## Safe Work Allowed

Codex may directly handle:

- Markdown documentation updates
- homepage copy improvements
- support page improvements
- footer and navigation fixes
- SEO metadata checks
- sitemap and robots.txt updates
- accessibility notes and test checklists
- simple CSS improvements
- small JavaScript repairs that preserve current behavior
- pet category pages
- educational pet content pages
- local ad planning documents before live ads
- affiliate planning documents before live monetization
- checkpoint and project-status updates

## Do Not Change Without Direct Approval

Do not do these without direct approval:

- framework conversion
- React, Vite, Next.js, TypeScript, npm, or build-tool migration
- major deletion of working site code
- payment setup
- live ads
- live tracking scripts
- accounts or logins
- private keys or API tokens
- veterinary diagnosis claims
- content that pretends to replace licensed veterinary care

## PetNeeds.ai Content Rules

Keep content clear, beginner-friendly, and family-safe.

Pet guidance must be educational only. It should encourage contacting a licensed veterinarian for illness, injury, poisoning, emergencies, or medical diagnosis.

Use plain language and practical steps for everyday pet owners.

## Current Safe Queue

1. Keep navigation simple and consistent.
2. Keep About, Contact, Privacy, Terms, and Affiliate Disclosure pages available.
3. Add useful pet content pages gradually.
4. Improve mobile layout and accessibility basics.
5. Keep content beginner-friendly and family-safe.
6. Avoid live ads, payment handling, private keys, and medical diagnosis claims until intentionally configured.
7. Add local ad and affiliate planning only as documentation until privacy and trust rules are ready.

## Reporting Rule

Commit useful safe changes. Report after several useful commits or when a real blocker appears.

Record blockers in `PROJECT-STATUS.md` instead of stopping early.
