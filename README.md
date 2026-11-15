# Digital Garden

Personal knowledge base built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/), organising book takeaways, high-level topic syntheses, and AI research notes.

## Structure

- `docs/books/` - Structured chapter notes by book (starting with *Sapiens*).
- `docs/topics/` - Cross-cutting topic syntheses grouped by domain.
- `docs/tags.md` - Automatic tag index across all notes.

## Local Preview

```bash
uvx --with mkdocs-material mkdocs serve
```

Or with a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```
