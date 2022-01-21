# markdown-link-check mirror

_This mirror is deprecated. Use the official pre-commit hook offered by [markdown-link-check](https://github.com/tcort/markdown-link-check) instead._

## Usage

Add this to your [`.pre-commit-config.yaml`](https://pre-commit.com/#2-add-a-pre-commit-configuration):

```yaml
- repo: https://github.com/tcort/markdown-link-check
  rev: ""
  hooks:
    - id: markdown-link-check
```

then run [`pre-commit autoupdate`](https://pre-commit.com/#updating-hooks-automatically).
