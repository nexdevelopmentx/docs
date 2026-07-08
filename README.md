# NEX.dev Documentation

The official documentation for NEX.dev's FiveM scripts — install guides,
configuration references, and troubleshooting for every resource.

## Editing

Pages are MDX files with YAML frontmatter, organized into one folder per script.
The sidebar and site settings live in `docs.json`.

## Local preview

Install the docs CLI:

```
npm i -g mint
```

Then run, from the repository root (where `docs.json` lives):

```
mint dev
```

The preview is served at `http://localhost:3000`.

## Publishing

Changes pushed to the default branch are deployed to production automatically.

## Useful commands

- `mint dev` — local preview
- `mint broken-links` — validate internal links
- `mint update` — update the CLI
