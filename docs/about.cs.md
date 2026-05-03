# O kuchařce

Tahle osobní kuchařka je postavená na [MkDocs](https://www.mkdocs.org/) a tématu [Material](https://squidfunk.github.io/mkdocs-material/).

## Přidání nového receptu

1. Zkopíruj `docs/recipes/_template.cs.md` do `docs/recipes/<slug>.cs.md` a napiš českou verzi.
2. Zkopíruj `docs/recipes/_template.en.md` do `docs/recipes/<slug>.en.md` a napiš anglickou verzi.
3. *(Volitelně)* Přidej obrázek do `docs/recipes/images/` a odkaž ho v receptu.
4. Přidej recept do sekce `nav` v `mkdocs.yml`.

## Lokální náhled

```bash
pip install -r requirements.txt
mkdocs serve
```
