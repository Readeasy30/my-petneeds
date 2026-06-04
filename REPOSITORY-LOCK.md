# Repository Stability Lock

Repo: `Wholelychit/my-petneeds`

Status: **LOCKED FOR STABLE, SAFE WORK ONLY**

## Core rule

Do not redesign, rebuild, or migrate this repository without direct owner approval.

## Allowed safe work

- Fix broken links.
- Fix typos and unclear copy.
- Improve accessibility.
- Improve mobile layout.
- Improve SEO metadata.
- Update README, AGENTS, status, checklist, and QA files.
- Add safe static content pages that match the existing site.
- Fix small HTML, CSS, or JavaScript bugs.

## Stop before doing these

- Do not add private keys, environment secrets, auth tokens, or credentials.
- Do not add live tracking scripts.
- Do not add live ad scripts.
- Do not add payment setup.
- Do not add affiliate links without direct approval.
- Do not add public AI tools, user accounts, uploads, or databases without direct approval.
- Do not add MCP machine config files.
- Do not convert the stack to React, Vite, Next.js, TypeScript, or another framework unless directly approved.
- Do not delete major working code.

## Stability process

1. Read this file first.
2. Read `AGENTS.md`, `PROJECT-STATUS.md`, and existing README files if present.
3. Make small safe commits.
4. Preserve the current working site.
5. Report changes in a table.

## Security file rule

`.gitignore` is part of this lock. Keep secret, local config, MCP, dependency, and private export files out of the repo.
