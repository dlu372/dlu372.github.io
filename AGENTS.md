# AGENTS.md

## Project purpose

This repository contains Di Lu's professional personal website. It presents experience, projects, education, and professional links in clear, natural English.

## Tech stack

- Astro with TypeScript
- Static site output
- Plain CSS and minimal client-side JavaScript

## Working guidelines

- Keep all user-facing website copy in natural, professional English.
- Keep the visual direction restrained, credible, and editorial, inspired by academic profile sites without copying another person's content or branding.
- Use `source-materials/profile.PNG` as the approved professional portrait unless the user explicitly replaces it.
- Treat files under `source-materials/` as source-of-truth materials. Do not modify or delete them.
- Prefer accessible semantic HTML, visible keyboard focus, sufficient contrast, and responsive layouts.
- Avoid unnecessary dependencies and client-side frameworks.
- External links should open in a new tab and include `rel="noreferrer"`.
- Do not publish, push, or configure the `dilu.site` domain unless the user explicitly requests it.

## Validation

Before handing work back:

1. Run `npm run build`.
2. Fix every build error and warning that indicates a real defect.
3. Confirm the local development server loads successfully.
