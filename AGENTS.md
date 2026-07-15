# Agent Guide for bongsal.github.io

## Project Overview

This repository is a personal portfolio and CV site for Kosal Koeung, a Senior Fullstack Developer. It is published as a GitHub Pages user site via the repository name `BongSal/bongsal.github.io`.

The entire site consists of a single Markdown file:

- `README.md` — The homepage content rendered by GitHub Pages. It contains the owner's contact information, professional summary, work experience, education, skills, and technologies.

There are no application frameworks, build pipelines, tests, or server-side components.

## Technology Stack

- **Hosting:** GitHub Pages (user site repository).
- **Source format:** Markdown.
- **Renderer:** GitHub Pages default Jekyll/Markdown rendering.
- **No build tools:** No `package.json`, `Gemfile`, `_config.yml`, `pyproject.toml`, `Cargo.toml`, or other build configuration files are present.
- **No dependencies:** Do not add third-party tooling without explicit user approval.

## Repository Structure

```
bongsal.github.io/
├── README.md    # CV / portfolio content (the only tracked file)
└── AGENTS.md    # This file
```

## Build and Deployment

- GitHub Pages automatically builds and deploys the `main` branch.
- No local build command is required.
- Changes to `README.md` are reflected on the live site after GitHub Pages finishes its publish cycle (usually within a minute or two).

## Editing Guidelines

- Keep the content in `README.md` in English, matching the existing style.
- The file is a CV, so updates should stay factual and professional.
- Use standard Markdown formatting:
  - `#` for the main title.
  - `##` for section headings.
  - `###` for individual job/project headings.
  - Tables for structured data such as education and skills.
  - Backticks for inline technology names.
- Preserve the existing sections: About, Experience, Education, Hard Skills, and Other Technologies.
- Verify Markdown rendering (headings, tables, lists) after any edit.

## Testing

There are no automated tests. Validate changes by:

1. Previewing the rendered Markdown locally or on GitHub.
2. Pushing to `main` and confirming the live GitHub Pages site displays correctly.

## Security Considerations

- The repository is public and the README contains personal contact information (phone, email, location). Do not add sensitive credentials, API keys, or private data.
- Any newly added files will also be public; avoid committing secrets, private notes, or draft content.
