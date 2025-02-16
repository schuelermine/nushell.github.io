---
title: path basename
layout: command
version: 0.63.0
usage: |
  Get the final component of a path
---

# `{{ $frontmatter.title }}`

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> path basename --columns --replace```

## Parameters

 -  `--columns {table}`: Optionally operate by column path
 -  `--replace {string}`: Return original path with basename replaced by this string

## Examples

Get basename of a path
```shell
> '/home/joe/test.txt' | path basename
```

Get basename of a path by column
```shell
> [[name];[/home/joe]] | path basename -c [ name ]
```

Replace basename of a path
```shell
> '/home/joe/test.txt' | path basename -r 'spam.png'
```
