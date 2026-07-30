---
site:
  hide_toc: true
  hide_outline: true
---

# Dependency groups

Some Python packages don't need to be installed by the end users, e.g. `ruff`.

Historically, people have used `project.optional-dependencies` for this:

![](#code:install-dep-group)

Now, we have dependency groups:

![](#code:dep-groups)

that we can install with

![](#code:install-dep-group)
