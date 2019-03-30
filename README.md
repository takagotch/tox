### tox
---
https://tox.readthedocs.io/en/latest/

```
[build-system]
requires = [ "setuptools >= 35.0.2", "wheel >= 0.29.0"]
build-backend = "setuptools.build_meta"

[tool.tox]
legacy_tox_ini = """
[tox]
envlist = py27,py36

[testenv]
deps = pytest >= 3.0.0, <4
commands = pytest
"""

[testenv]
platform = linux2|darwin

[testenv]
whitelist_externals = make
  /bin/bash
```

```
```

```
```


