---
title: dfr ls
layout: command
version: 0.63.0
usage: |
  Lists stored dataframes
---

# `{{ $frontmatter.title }}`

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> dfr ls ```

## Examples

Creates a new dataframe and shows it in the dataframe list
```shell
> let test = ([[a b];[1 2] [3 4]] | dfr to-df);
    dfr ls
```
