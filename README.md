# pre-commit-nushell

[pre-commit][] hooks for [nushell][] scripts (and nuon)

`.pre-commit-config.yaml`:
```yaml
repos:
  - repo: https://github.com/jan9103/pre-commit-nushell.git
    rev: v0.1
    hooks:
      - id: check-nu-ast
```


[pre-commit]: https://pre-commit.com
[nushell]: https://nushell.sh
