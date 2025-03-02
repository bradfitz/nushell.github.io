---
title: bits or
categories: |
  bits
version: 0.84.0
bits: |
  Performs bitwise or for integers.
usage: |
  Performs bitwise or for integers.
---

# <code>{{ $frontmatter.title }}</code> for bits

<div class='command-title'>{{ $frontmatter.bits }}</div>

## Signature

```> bits or (target)```

## Parameters

 -  `target`: target integer to perform bit or


## Input/output types:

| input     | output    |
| --------- | --------- |
| int       | int       |
| list\<int\> | list\<int\> |
## Examples

Apply bits or to two numbers
```shell
> 2 | bits or 6
6
```

Apply logical or to a list of numbers
```shell
> [8 3 2] | bits or 2
╭───┬────╮
│ 0 │ 10 │
│ 1 │  3 │
│ 2 │  2 │
╰───┴────╯

```


**Tips:** Command `bits or` was not included in the official binaries by default, you have to build it with `--features=extra` flag