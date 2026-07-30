---
site:
  hide_toc: true
  hide_outline: true
---

# Dependency hell

Poetry is a popular tool for project management.
It _loves_ defining upper bounds.

![](#code:pyproject-cap)

Python environments can only have one version of a package.

Constraints add together to form _stricter_ constraints.

![](#note:overlap-constraints)
