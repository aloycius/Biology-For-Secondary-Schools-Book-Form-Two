# Conversion Manifest

## Book

- Title/source identifier: Biology Form 2 New Final
- Source file: `/Users/aloyciuslaurent/Desktop/Form Two Books/BIOLOGY FM 2 SB/BIOLOGY FORM 2 NEW final.pdf`
- File size observed: 14 MB
- PDF version observed: 1.4
- ADT book label: `biology-form-2-new-final`
- Book directory: `/Users/aloyciuslaurent/adt-studio/books/biology-form-2-new-final`

## Workflow

Use ADT Studio headlessly from `/Users/aloyciuslaurent/adt-studio`.

```bash
pnpm pipeline biology-form-2-new-final "/Users/aloyciuslaurent/Desktop/Form Two Books/BIOLOGY FM 2 SB/BIOLOGY FORM 2 NEW final.pdf" --books-dir "/Users/aloyciuslaurent/adt-studio/books"
```

## Publication Boundary

This repository is a coordination repository only until the book is converted and audited. Do not commit:

- The source PDF
- SQLite databases or entity histories
- LLM caches, prompts, responses, or logs
- API keys or `.env` files
- Temporary renders, audit screenshots, or local absolute-path debug output

After audit, publish only a clean, self-contained static web bundle when explicitly authorized.
