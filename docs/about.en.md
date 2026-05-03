# About

This is a personal cookbook built with [MkDocs](https://www.mkdocs.org/) and the [Material](https://squidfunk.github.io/mkdocs-material/) theme.

## Adding a new recipe

1. Copy `docs/recipes/_template.en.md` to `docs/recipes/<slug>.en.md` and write the English version.
2. Copy `docs/recipes/_template.cs.md` to `docs/recipes/<slug>.cs.md` and write the Czech version.
3. *(Optional)* Drop a picture into `docs/recipes/images/` and reference it from the recipe.
4. Add the recipe to the `nav` section in `mkdocs.yml`.

## Local preview

```bash
pip install -r requirements.txt
mkdocs serve
```
