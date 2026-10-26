# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

@AGENTS.md

## Notes beyond AGENTS.md

- The site is just `README.md` rendered by GitHub Pages; there is nothing to build or test. Pushing to `main` deploys.
- `README.md` starts with `<!-- markdownlint-disable MD013 MD026 MD033 MD041 -->` (long prose lines, "Co., Ltd." headings, centered header div). Keep it lint-clean: `npx -y markdownlint-cli2 README.md`.
- Content conventions in `README.md` to keep when editing:
  - Each job is `### Role — Company` (em dash), followed by a date line (`📅 **Mon YYYY – Present**`, en dash; the emoji keeps markdownlint MD036 quiet), a short description, then project bullets starting with `**Project Name:**`.
  - The header (name, title, contact row, core-stack chips) is wrapped in `<div align="center" markdown="1">` with blank lines inside so both GitHub and Jekyll parse the Markdown.
  - Project descriptions start with an action verb (Built / Designed / Delivered …).
  - Per-project tech lines are indented continuation lines of backticked chips (`  **Tech:** \`NestJS\` \`Nuxt\``) under the bullet; job-wide tech goes in one `**Stack:**` chip line after the bullet list. No trailing-space line breaks are used.
  - Use official tech names: NestJS, Nuxt, Node.js, PostgreSQL, MySQL, Capacitor.js.
  - Sections are separated by `---` horizontal rules.
  - Skills is a two-column `Area | Technologies` table of backticked chips grouped by area (no self-rated levels). Keep table columns padded and aligned.
- Newest experience goes first.
