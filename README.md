# Cookbook

Personal cookbook built with [MkDocs](https://www.mkdocs.org/) and the [Material](https://squidfunk.github.io/mkdocs-material/) theme. Available in English and Czech.

## Local development

```bash
pip install -r requirements.txt
mkdocs serve
```

Open <http://127.0.0.1:8000>.

## Build

```bash
mkdocs build
```

The static site lands in `site/`.

## Adding a new recipe

1. Pick a slug, e.g. `gulas`.
2. Copy `docs/recipes/_template.en.md` → `docs/recipes/gulas.en.md` and translate.
3. Copy `docs/recipes/_template.cs.md` → `docs/recipes/gulas.cs.md` and translate.
4. *(Optional)* Drop a picture into `docs/recipes/images/`.
5. Add the page to `nav` in `mkdocs.yml`.

Each recipe has the same structure: **ingredients**, an **optional picture**, and a **step-by-step** guide.
