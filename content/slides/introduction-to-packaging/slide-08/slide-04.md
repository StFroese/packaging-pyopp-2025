---
site:
  hide_toc: true
  hide_outline: true
---

# Backsolving

How do we solve the following problem?

1. I want `numpy>=2` in my new package
2. I also want `arrow-to-knee`
3. `arrow-to-knee==1.0.1` wants `numpy>=1,<2`

Python will {term}`back solve<back solving>` to get `arrow-to-knee==1.0.0`!

![](#warning:back-solving-not-intentional)

This is "dependency hell"
