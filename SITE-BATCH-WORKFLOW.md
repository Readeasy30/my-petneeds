# PetNeeds.ai Site Batch Workflow

Date: 2026-05-29

## Goal

Move PetNeeds.ai forward in grouped work sessions instead of one tiny change at a time.

The site stays on the current static setup and continues to use simple files that are easy to maintain.

## Build stack

- HTML pages
- CSS in `styles.css`
- GitHub for commits
- Cloudflare Pages for publishing from GitHub

## Batch method

1. Read the project docs first.
2. Group related page edits together.
3. Commit useful groups of changes.
4. Keep the public site stable after each group.
5. Record progress in `PROJECT-STATUS.md`.

## Page cleanup batch

Apply this sweep to the public pages listed in `sitemap.xml`.

For each page:

1. Confirm the page has one title.
2. Confirm the page has one meta description.
3. Add the matching canonical URL.
4. Confirm the page links to `styles.css`.
5. Keep header links easy to use.
6. Keep footer links consistent.
7. Use the existing `.footer-note` class for the short page footer note.
8. Keep copy clear for normal families and beginner pet owners.

## Canonical URL pattern

Use the live domain plus the page file name.

Examples:

- Home page: `https://petneeds.ai/`
- Puppy page: `https://petneeds.ai/puppy-starter-checklist.html`
- Contact page: `https://petneeds.ai/contact.html`

## Current public page set

- `index.html`
- `starter-guides.html`
- `puppy-starter-checklist.html`
- `kitten-starter-checklist.html`
- `fish-tank-starter-checklist.html`
- `senior-pet-comfort-checklist.html`
- `rescue-first-week-checklist.html`
- `dogs.html`
- `dog-comfort-checklist.html`
- `cats.html`
- `fish.html`
- `birds.html`
- `reptiles.html`
- `small-pets.html`
- `senior-pets.html`
- `rescue.html`
- `ask-ai.html`
- `emergency.html`
- `upload-photo.html`
- `about.html`
- `privacy.html`
- `terms.html`
- `contact.html`
- `affiliate-disclosure.html`

## Future feature boundaries

Future business features should stay as planning notes until their pages, disclosures, settings, and test steps are ready.

This includes revenue tools, visitor accounts, file submission tools, automated answer tools, ordering tools, and outside service connections.

## Verification checklist

After each batch:

1. Open the changed files in GitHub.
2. Confirm internal links use the correct `.html` file names.
3. Confirm sitemap entries match real files.
4. Confirm public pages load the shared stylesheet.
5. Confirm the footer is present.
6. Confirm `PROJECT-STATUS.md` reflects the completed work.

## Reporting

At the end of a batch, report:

- files changed
- commit hashes
- what remains next
- any true repository problem that stopped progress