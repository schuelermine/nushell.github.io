---
title: math variance
layout: command
version: 0.63.0
usage: |
  Finds the variance of a list of numbers or tables
---

# `{{ $frontmatter.title }}`

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> math variance --sample```

## Parameters

 -  `--sample`: calculate sample variance

## Examples

Get the variance of a list of numbers
```shell
> echo [1 2 3 4 5] | math variance
```

Get the sample variance of a list of numbers
```shell
> [1 2 3 4 5] | math variance -s
```
