---
title: export
layout: command
version: 0.63.0
usage: |
  Export custom commands or environment variables from a module.
---

# `{{ $frontmatter.title }}`

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> export ```

## Notes
```text
This command is a parser keyword. For details, check
https://www.nushell.sh/book/thinking_in_nushell.html#parsing-and-evaluation-are-different-stages
```
## Examples

Export a definition from a module
```shell
> module utils { export def my-command [] { "hello" } }; use utils my-command; my-command
```
