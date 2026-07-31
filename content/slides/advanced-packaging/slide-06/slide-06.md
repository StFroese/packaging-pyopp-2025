---
site:
  hide_toc: true
  hide_outline: true
---

# JupyterLite

An easy way to get started with Python on the web is `jupyterlite`:

```{code} bash
jupyter lite build --contents=notebooks
```

This produces a static website that can live on GitHub Pages, ReadTheDocs, etc.

You can use `environment.yaml` or `requirements.txt`, or `micropip install` in each notebook.

{button}`Try JupyterLite<https://jupyter.org/try-jupyter/lab/?path=notebooks%2FIntro.ipynb>`
