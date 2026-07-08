# NEX.dev docs — project instructions

## About this project

- Documentation for NEX.dev's FiveM scripts.
- Pages are MDX files with YAML frontmatter; one folder per script.
- Navigation and site configuration live in `docs.json`.

## Structure

- One folder per resource (e.g. `nex-garage/`, `nex-queue/`), each with an
  `overview` page plus pages like `installation`, `configuration`,
  `troubleshooting`.
- Shared pages live under `general/`; release notes under `changelog/`.
- Internal links are root-relative and omit the file extension
  (e.g. `/nex-garage/installation`).

## Terminology

- Refer to products by their full name: "NEX Garage", "NEX Queue", etc.
- "Resource" or "script" for a FiveM resource; "framework" for QBCore / Qbox / ESX.

## Style preferences

- Use active voice and second person ("you").
- Keep sentences concise — one idea per sentence.
- Use sentence case for headings.
- Bold for UI elements: Click **Settings**.
- Code formatting for file names, commands, paths, and config keys.
- Use callouts (`<Info>`, `<Warning>`, `<Danger>`) for notes and cautions.

## Branding

- Colors are black (`#000000`) and white (`#FFFFFF`).
- Logos: `logo/nex-black.png` (light mode), `logo/nex-logo.png` (dark mode).
