---
site:
  hide_toc: true
  hide_outline: true

kernelspec:
  name: python3
  display_name: Python 3
---

# How does CPython work?

Most people use CPython. It uses a <wiki:virtual_machine> to execute Python code instructions.

```{code-cell} python3
def some_func():
    print("Hello world!")
```

Let's ask Python to show us the bytecode:

```{code-cell} python3
import dis
dis.dis(some_func)
```
