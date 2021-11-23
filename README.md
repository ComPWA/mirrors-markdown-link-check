# markdown-link-check mirror

Mirror of [`markdown-link-check`](https://github.com/tcort/markdown-link-check)
for [pre-commit](https://pre-commit.com), created with
[`pre-commit-mirror-maker`](https://github.com/pre-commit/pre-commit-mirror-maker).

## Usage

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/ComPWA/mirrors-markdown-link-check
  rev: ""
  hooks:
    - id: markdown-link-check
```

then run `pre-commit autoupdate`.

The tool can be configured with a `.markdown-link-check.json`, formatted as
explained
[here](https://github.com/tcort/markdown-link-check#command-line-tool).
