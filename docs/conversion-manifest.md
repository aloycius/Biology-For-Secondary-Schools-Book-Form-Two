# Conversion Manifest

## Book

- Title/source identifier: Biology Form 2 New Final
- Source file: stored locally outside this repository
- File size observed: 14 MB
- PDF version observed: 1.4
- ADT book label: `biology-form-2-new-final`
- Book directory: the ADT Studio `books/biology-form-2-new-final` directory

## Workflow

Use ADT Studio headlessly from the ADT Studio repository root.

```bash
pnpm pipeline biology-form-2-new-final "<absolute-path-to-source-pdf>" --books-dir "<absolute-path-to-adt-studio>/books"
```

## Publication Boundary

This repository is a coordination repository only until the book is converted and audited. Do not commit:

- The source PDF
- SQLite databases or entity histories
- LLM caches, prompts, responses, or logs
- API keys or `.env` files
- Temporary renders, audit screenshots, or local absolute-path debug output

After audit, publish only a clean, self-contained static web bundle when explicitly authorized.
