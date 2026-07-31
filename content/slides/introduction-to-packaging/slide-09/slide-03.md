---
site:
  hide_toc: true
  hide_outline: true
---

# Uploading a package

[Earlier](#sec:build-distribution) we built a {term}`source distribution` and a {term}`binary distribution`.

Now we can upload those to PyPI. We'll use [test.pypi.org](https://test.pypi.org).

```{code} bash
:label: code:publish-test
$ hatch publish -r test
Username for 'https://test.pypi.org/legacy/' [__token__]: __token__
Password / Token:
```

For 2FA, you'll need to create an API token:

![The Add API token button on PyPI](/media/token.png)
