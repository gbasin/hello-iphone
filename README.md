# Steve Jobs iPhone 2007 Slidev Study

This repo rebuilds the 2007 iPhone launch as a Slidev study deck. It merges:

- the supplied presentation transcript
- rendered visuals from the companion slide PDF
- an analysis layer explaining Jobs' launch mechanics

## Run

```bash
npm install
npm run dev
```

Then open `http://localhost:3030/`.

## Build

```bash
npm run build
```

The generated site is written to `dist/`, which is intentionally ignored.

## Files

- `slides.md` - the Slidev deck
- `style.css` - custom visual system
- `assets/source-slides/` - rendered pages from the companion PDF
- `source/` - extracted text from the supplied PDFs
- `SKILL.md` - reusable method for this presentation-analysis style

## Notes

The deck uses short transcript excerpts as the spine and treats visuals as evidence, not decoration. Each analytical slide names a presentation move, shows the source visual, and explains why the move works.
